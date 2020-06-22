# FRONTEND-BASIC

### Wat is HTML

HTML staat voor Hyper Text Markup Language. Het is een opmaaktaal en niet echt een programmeertaal. Deze taal wordt uitgevoerd in de browser.

Een webpagina is opgebouwd uit HTML-tags. Tags kun je vergelijken met Lego blokjes. Net als bij Lego kun je hiermee de **STRUCTUUR** van een website bepalen.

![lego](/FRONTEND-BASIC/03%20-%20Basis%20HTML/taak01/images/lego.jpg)

De meeste webpagina's die jij gaat maken hebben een standaard patroon.

Een webpagina heeft vaak het volgende standaard patroon:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Mijn eerste webpagina</title>
  </head>
  <body>
  
  </body>
</html>
```

De volgende tags zijn **altijd** aanwezig op je website:

> `<!DOCTYPE html>` : tag die aangeeft dat je op deze pagina HTML versie 5 gebruikt

> `<html>` : tag die aangeeft dat je html tags gaat gebruiken

> `<head>` : tag waarin belangrijke informatie staat, deze informatie is voor een normale gebruiker niet zichtbaar

> `<title>` : tag waarin de titel van de webpagina genoteerd wordt

> `<body>` : tag waar alle **zichtbare** informatie gezet wordt

Zoals je ziet hebben de bovenstaande `tags` ook nog _sluit_-tags. Dit zijn tags met een `/` ervoor. Dus bijvoorbeeld `</body>`. Dit betekent het **einde** van dit onderdeel.

> Kortom: (Bijna) alle tags hebben een sluit-tag:

```html
<html></html>
<head> </head>
<title> </title>
<body></body>
<h1></h1>
<p></p>
```

Tussen de tags zet je informatie neer die daar hoort (zie `<title>` eerste voorbeeld).

In de `<body>` tag zet je informatie neer waar je klant of gebruiker wat aan heeft. Bijvoorbeeld zo:

```html
<body>
  <h4>Hier komt voor de gebruiker zichtbare informatie te staan</h4>
  <p>Dit is een paragraaf</p>
</body>
```
Dit is dan het resultaat:
![eerste webpagina](/FRONTEND-BASIC/03%20-%20Basis%20HTML/taak01/images/index.png)


### OPDRACHT

1.
