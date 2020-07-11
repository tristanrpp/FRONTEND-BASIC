# FRONTEND-BASIC

## BASIS CSS-TAAK-04

### Class gebruiken

Bij de vorige opdracht heb je alle `<h4>` tags dezelfde stijl gegeven. Dit geldt ook voor alle `<p>` tags. Je kunt elke afzonderlijke of een paar `<p>` tags anders stijlen als je dat zou willen. Dat doe je met het __class__ attribuut.

Stel je alleen de artikelen over Amsterdam anders wilt stijlen, omdat het bijvoorbeeld niet over sport gaat. Dan kun je met een ___class__ attribuut deze specifieke tags anders stijlen.

Een class is een eigenschap van een tag. Je schrijf het zo:
> class="amsterdam"
>
```html
<p class="amsterdam">De tekst komt hier</p>
<p >Hier staat weer andere tekst</p>
```

Als je de tag met die class wilt stijlen dan kan je dat in CSS doen met een __`.`__

```css
    .amsterdam{
        color: red;
    }

```

Zie je dat een punt vooraf gaat aan het woord _amsterdam_

Kijk ook eens naar onderstaande afbeelding:

![Classes](images/class_amsterdam.png)

### OPDRACHT

1. Maak gebruik van je gemaakt werk bij taak03
2. Geef de tags die gaan over Amsterdam de class _amsterdam_.
3. Stijl die tags met een andere kleur.
4. Wat is je eindresultaat?

### BRONNEN

- [Classes gebruiken (.) - Les 3](https://www.youtube.com/watch?v=E--hpftoXKc)
