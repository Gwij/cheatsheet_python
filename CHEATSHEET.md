# Variabelen

Variabelen laten je toe om informatie op te slaan in Python.

## Variabelen maken

De naam van een variabele kan je vrij kiezen zolang ze aan de volgende regels voldoet.

- De naam moet bestaan uit een combinatie van cijfers, letters of underscores ('_').
- Het eerste karakter van de naam moet een letter zijn.

Je kent een waarde toe aan de variabele door de gelijkheid te gebruiken ('=').

```python
mijn_getal = 10
```

## Variabelen gebruiken

Je kan via de naam van een variabele zijn waarde gebruiken in bijvoorbeeld berekeningen.

```python
getal_1 = 5
getal_2 = 6
som = getal_1 + getal_2
```

## Variabele aanpassen

Je kan de waarde van een variabele aanpassen door een nieuwe waarde toe te kennen aan de variabele.

```python
getal = 10
getal = 16 # De waarde van getal is nu 16.
```

Merk op dat je bij het aanpassen van de waarde ook gebruik kan maken van de oude waarde.

```
getal = 10
getal = getal + 5 # De waarde van getal is nu 15.
```

# Input en output

## Tekst printen

Je kan **tekst** op het scherm zetten door middel van de `print()` functie.

```python
print("Hello world!")
```

Merk op dat de `print()` functie enkel waarden van het type `string` accepteert. Je zal dus eerst de waarde moeten omzetten naar `string`.

## Invoer vragen aan de gebruiker

Je kan invoer vragen aan de gebruiker door middel van de `input()` functie. De `input()` functie kan als parameter een tekst aannemen die getoond wordt aan de gebruiker. De `input()` functie geeft als return de ingevoerde **tekst** van de gebruiker.

```python
input("Geef een getal:")
```

Merk op dat de `input()` functie altijd een return waarde heeft van het type `string`. Stel dat je wilt dat de gebruiker een getal invoert voor een berekening dan moet je eerst het ingevoerde getal omzetten naar een het `int` of `float` type vooraleer je er berekeningen mee kan doen.

# Types

Elke waarde in Python heeft een type. Een type kan je zien als de soort of categorie van de waarde. Zo zal de waarde `5` horen bij de categorie van getallen en de waarde `"Tim"` horen bij de categorie van tekst. We zetten even de belangrijkste types op een rijtje:

- **int**: integer, type voor gehele getallen (4, 10, -1, 0, ...)
- **float**: floating point number, type voor kommagetallen (1.23, -1.23, 0.0, ...)
- **bool**: boolean, type voor booleaanse waarden (True of False)
- **str**: string, type voor tekst ("Hoi", "Tim", "", ...)

## Type opvragen

Je kan het type van een waarde opvragen door middel van de `type` functie.

```python
print(type("Hello")) # Print str
print(type(5)) # Print int
```

## Type veranderen

Je kan het type van een waarde veranderen door de conversie functie te gebruiken overeenkomend met het type waarnaar je wilt veranderen. In Python komt de naam van deze functie steeds overeen met het type. Dus om het type naar `int` aan te passen kan je de `int()` functie gebruiken. Merk op dat je niet het type van elke waarde zomaar naar om het even welk type kan aanpassen. Experimenteer met wat wel mogelijk is en wat niet.

```python
mijn_tekst = "5" # Dit is tekst en dus van het type str
mijn_getal = int(mijn_tekst) # We zetten de tekst om naar een getal. Dit is dus nu van het type int.
som = mijn_getal + 2 # We kunnen nu berekeningen uitvoeren met de omgezette waarde.
```

# Functies

Een functie is een blokje code die je herhaaldelijk kan oproepen.

## Functie maken en oproepen

Je maakt een functie door middel van het `def` keyword. Na de `def` zet je de naam van de functie, gevolgd door haakjes `()` en een dubbele punt `:`. Na de dubbele punt kom het blokje code ofwel de inhoud van de functie. Een blok code moet je steeds indenteren. Dit betekent dat je

# Lijsten



# Lussen

# Beslissingen
