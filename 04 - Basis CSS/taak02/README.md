# FRONTEND-BASIC

### Introductie CSS

Je kunt de achtergrond van een webpagina een kleur geven. Door de volgende code te schrijven: `background-color`. Daarnaast kun je ook tekst een kleur geven door `color` te gebruiken.

Hier volgt een voorbeeld

```CSS
body{
    background-color: green;
    color: purple
}
```

CSS kun je op verschillende manieren 'aan de pagina koppelen':

1. Inline
2. Blok
3. Extern

Op dit moment gebruiken we alleen nog de blok-manier. Deze begin je met een `<style>` tag en sluit je af met `</style>` sluit tag

```html
<style>
    /* hier komt je css te staan */ 
    body{
        background-color: green;
        color: purple
    }
</style>
```

Je plaatst je CSS blok tussen de  `<head>` tags van je pagina.

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Mijn eerste CSS</title>
        <style>
            /* hier komt je css te staan */ 
            body{
                background-color: green;
                color: purple
            }
        </style>
    </head>
    <body>
    <!-- Je codeert je plaatje onder deze regel -->
    </body>
</html>
```
### OPDRACHT

1. Maak een index.html bij deze taak
2. Gebruik de standaard HTML tags
3. Maar in de body een `<h1>`-tag en een `</h1>`-sluit tag met daarin de volgende tekst: `"De meeste mensen deugen"`
4. Geef de achtergrond een rode kleur
5. Geef de tekst een gele kleur
