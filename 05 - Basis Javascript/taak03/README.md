# FRONTEND-BASIC

## BASIS JAVASCRIPT-TAAK-03

### Variabelen

Je hebt bij de vorige opdracht code gemaakt dat een bepaalde __ouput__ genereerd. Je codeerde, afhankelijk van het type popup-box, een bepaalde __input__ van de gebruiker. Bij promp() kon de gebruiker naast Ok-knop ook iets invullen.

Maar met deze input werd nog niks gedaan. Dat ga je bij deze opdracht coderen.

Om de input van zo'n _tekstveld_ te krijgen gebruiken we bij deze opdracht een __variabele__. Dat is een soort doosje waar je data in kan opslaan om later weer te gebruiken. In alle programmeertalen bestaan variabelen.

Het heet varaiabele omdat de inhoud kan veranderen.

Om een variabele te maken gebruiken we uiteraard Javascript. De volgende schrijfwijze:

```html
<script>
    let mijnVoornaam = "David";
</script>
```

Met deze code staat er `David` in de variabele `mijnVoornaam`.

Ook hier is een specifieke schrijfwijze gebruikt:

- de naam van de variabele begint met een kleine letter
- het tweede woord in een variabele is een hoofdletter mijn`V`oornaam
- een `=` teken wordt gebruikt om de variable te 'vullen'
- een woord of zin zet je tussen `"` en `"`
- een getal hoef je niet tussen aanhalingstekens te zetten
- een regel eindigt met een `;`

Dit is een beetje saaie code, we willen tenslotte aan elke gebruiker zijn of haar naam opvragen met de prompt-box

```html
<script>
    let mijnVoornaam = prompt("Vul je voornaam in aub");;
</script>
```

Nu wordt de input van de gebruiker (`voornaam`) gestopt in het doosje `mijnVoornaam`

> We doen nog verder niks met de variabele maar dat gaan we wel doen.

Zie dat het woordje `let` is gebruikt? Dit is het woordje waarmee je een variabele kunt maken. Hieronder een paar voorbeelden

```js
let mijnLeeftijd = 42;
let mijnAchternaam = "van Oudheusden";
let merkAuto = "BMW";
```

### OPDRACHT

1. Open `index.html` in je browser.
2. Geef je naam op. Wat zie je daarna gebeuren?
3. Bestudeer de code eens.

### RESULTAAT

![Variabele](images/variabele.png)
