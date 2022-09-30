---
title: "XSS"
---

# XSS
## Definition
>XSS het het injecteren van javascript in een webpagina en staat voor Cross (X) site scriptin

**Types of XSS:**
	-   Stored
	-   Reflected
	-   DOM
**Detection:**
1. Waar gaat de data naartoe? Wordt het opgeslagen? Komt het terug op de pagina?
2. Hoe wordt data gehandled? word iets veranderd naar een link?
3. Hoe worden speciale characters gebruikt? Probeer eerst `<>;:` 
	- Schrijf op als er iets niet encode wordt zoals <
4. Als je in een atrribuut zit, bvb `<img src" -- HIER -- ">`  kan je er met " uit, als dat niet lukt gewoon door. 
5. Zit je in een script? Kan je uit de string? Zo niet dan secure
6. Gebruik DOM events zoals 
```html
onmouseover=alert(1)
<!-- Als je de url kan veranderen: -->
<a href="http://www.uwu.nl"></a>
<!-- met een payload zoals -->
http://"onmouseover="alert(1);
<a href="http://"onmouseover="alert(1);"></a>
```

- Exploitation
- Mitigation


## Backlinks

## Refrences:

---
Tags: #Concept #XSS #Uni #BugBounty 