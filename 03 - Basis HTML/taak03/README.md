# FRONTEND-BASIC

### Links maken

Ok. je hebt nu een taak gedaan met een basis pagina en een taak waarbij je een plaatje invoegd in je pagina.
In deze taak gaan we twee webpagina's aan elkaar linken.

Het gehele online web bestaat uit links. Als je ergens op klikt dan klik je op een URL-link. (Uniform Resource Locator).
Een link wordt ook wel een `anchor-tag` genoemd. Een anker of een haakje. Een haakje naar iets anders toe.

Een link heeft ook een _attribuut_, net als bij `<img>` waarbij `src` gebruikt werd, heeft een anchor-tag `<a>` een `href` attribuut. 

Bij `href` zet je de lokatie van een pagina neer, voorbeelden zijn:

- https://www.rocva.nl
- https://www.eagledev.nl
- https://www.outlook.com

Maar ook

- link_naar_andere_pagina.html
- tweede_pagina.html

Al deze `url`s staan tussen aanhalingstekens, net als bij `<img>`

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mijn eerste link</title>
  </head>
  <body>

    <a href="link_naar_andere_pagina.html">Link naar pagina 2</a>

  </body>
</html>
```

Met dit resultaat:

![Link](images/link.png)

Als je op deze link klikt dat wordt pagina `link_naar_andere_pagina.html` opgevraagd en getoond. Met natuurlijk de daarbij behorende informatie.

### OPDRACHT

1. Maak bij deze taak gebruik van bestand: `index.html` en van het bestand `over-mij.html`
2. Codeer een link op de index.html pagina naar over-mij.html toe. 
3. Houd je aan de schrijfwijze, dus met aanhalingstekens en naam.extentie

### EINDRESULTAAT

![eerste webpagina](images/resultaat.png)

### BRONNEN

- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
