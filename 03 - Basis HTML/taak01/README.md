# FRONTEND-BASIC

### Wat is HTML

HTML staat voor Hyper Text Markup Language. Het is een opmaaktaal. Deze taal wordt uitgevoerd in de browser.

Een webpagina is opgebouwd uit HTML-tags. Tags kun je vergelijken met Lego blokjes. Net als bij Lego kun je hiermee de **STRUCTUUR** van een website bepalen.

![lego](images/lego.jpg)

De meeste webpagina's die jij gaat maken hebben een standaard patroon.

Een webpagina heeft vaak het volgende standaard patroon. Deze HTML-tags zijn **altijd** aanwezig op je website:

```html
<!DOCTYPE html>
<html>
  <head>
    <title></title>
  </head>
  <body></body>
</html>
```

> `<!DOCTYPE html>` : tag die aangeeft dat je op deze pagina HTML versie 5 gebruikt

> `<html>` : tag die aangeeft dat je html tags gaat gebruiken

> `<head>` : tag waarin belangrijke informatie staat, deze informatie is voor een normale gebruiker __niet zichtbaar__

> `<title>` : tag waarin de titel van de webpagina genoteerd wordt

> `<body>` : tag waar alle **zichtbare** informatie gezet wordt

Zoals je ziet hebben de bovenstaande `tags` ook nog _sluit_-tags. Dit zijn tags met een `/` ervoor. Dus bijvoorbeeld `</body>`. Dit betekent het **einde** van dit onderdeel.

> Kortom: (Bijna) alle tags hebben een sluit-tag:

```html
<html></html>
<head></head>
<title></title>
<body></body>
<h1></h1>
<p></p>
```

Tussen de tags zet je informatie neer die daar hoort.

In de `<body>` tag zet je informatie neer waar je klant of gebruiker wat aan heeft. Bijvoorbeeld zo:

```html
<body>
  <h4>Hier komt voor de gebruiker zichtbare informatie te staan</h4>
  <p>Dit is een paragraaf</p>
</body>
```

Dit is dan het resultaat:
![een voorbeeld](images/index.png)

### OPDRACHT

1. Maak bij deze taak gebruik van bestand: `index.html`
2. Maak gebruik van de standaard tags en vul de volgende informatie in op de juiste plek, kies uit `title`, `h1` en `p` tags
   > - Een webpagina maken is makkelijk
   > - Welkom op mijn website.
   > - U moet nog even geduld hebben. De styling komt later
3. Lees de tekst en de opdracht goed om tot het eindresultaat te komen
4. Let erop dat de tag `title` tusse de `head` tags komt te staan
5. Let erop dat de `h1` en `p` tags tussen de `body` tags komen te staan

### EINDRESULTAAT

![eerste webpagina](images/resultaat.png)

### BRONNEN

- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)
