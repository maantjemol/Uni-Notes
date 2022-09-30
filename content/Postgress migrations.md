---
title: "Postgress migrations"
---

# Postgress migration 
## Server-config
ga eerst naar `/server-config` en checkout feature/postgress
```bash
git checkout feature/postgress
```

kopieer de json hieronder naar `~/.docker/config.json`
```json
{
        "auths": {
                "docker.zorgverkeer.nl:5443": {
                        "auth": "ZG9ja2VyOlJlZThpZzZh"
                }
        }
}
```

Voer in de `/server-config` map het install.sh script uit:
```bash
./install.sh development network services
```
-> als je de error `psql: error: could not connect to server:` krijgt bovenstaande command nogmaals uitvoeren 

## Hub 
Ga naar het mapje `hub.zorgverkeer.nl`
Checkout testing branch:
```bash
git checkout testing
```

Compile de server:
```bash
./compile.sh
```

Log in met een database client(DBeaver) in de postgress database. 
```
Host: localhost
database: zorgverkeer_development
Username: postgress
```

Voeg een nieuw schema toe met de naam processing, voer de query hieronder uit
```sql
create extension "mysql_fdw"
```

Log in bij de postgress server met de volgende gegevens:
```
Host: localhost
database: zorgverkeer_testing
Username: zorgverkeer
authentication: Database native 

In het SSH menu:
Host/ip: testing.zorgverkeer.nl:22
username: root
authentication method: public key 
private key: your private ssh key
passphrase: empty
```

Na het inloggen een export/backup maken van de database zorgverkeer testing. Dit kan in DBeaver bij tools en backup.
restore deze backup vervolgends bij de zorgverkeer_development database.

run de server:
```bash
./run.sh --http-server
```
