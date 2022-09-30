---
title: "DevEnv"
---

# Dev Env:
## stappen om hub.zorgverkeer.nl te starten:
### Docker:
Open Docker Desktop en start `Zorgverkeer-redis-development` en `Zorgverkeer-mysql-development`

### Processor / back-end
Ga naar de dir van Zorgverkeer in WSL: 
```bash
zv
``` 
Ga naar de processor directory:
```bash
cd hub.zorgverkeer.nl/processor
``` 
Start de processor:
```bash
./run.sh --http-server
```

### React / front-end
Ga naar de React directory (in powershell):
```bash
cd .\Documents\Zorgverkeer\hub.zorgverkeer.nl\react-dashboard\
``` 
Start de front-end:
```bash
npm start
```