# Variabelen

## Inleiding

In Python is een variabele een naam die wordt gebruikt om een waarde op te slaan. Je kunt het beschouwen als een container waarin je gegevens kunt bewaren en waarnaar je kunt verwijzen met behulp van die naam. Variabelen stellen je in staat om waarden op te slaan, te wijzigen en te manipuleren tijdens de uitvoering van een programma.

> **Opmerking.** In Python hoef je geen specifiek type aan een variabele toe te wijzen. De type-inferentie in Python stelt je in staat om een waarde aan een variabele toe te kennen, en de variabele krijgt automatisch het juiste type op basis van de toegewezen waarde. Voor meer informatie over types in Python kan je [deze](../TYPES.md) pagina raadplegen.

Hier is een voorbeeld van het maken en toewijzen van een variabele in Python:

```[Python]
bericht = "Hello world!"
```

In dit voorbeeld is `bericht` de naam van de variabele en `"Hello, World!"` is de waarde die aan de variabele is toegewezen. Vanaf dat punt kun je de variabele `bericht` gebruiken om naar de opgeslagen waarde te verwijzen.

Je kunt de waarde van een variabele wijzigen door deze opnieuw toe te wijzen:

```[Python]
bericht = "Hello Python!"
```

De naam van een variabele kan je niet zomaar vrij kiezen. Bij het benoemen van variabelen in Python moeten enkele regels en conventies worden gevolgd. Hier zijn de belangrijkste regels voor het benoemen van variabelen in Python:

1. Geldige tekens: Een variabelenaam kan bestaan uit letters (a-z, A-Z), cijfers (0-9) en het underscore-teken (_). Het is belangrijk om te weten dat variabelen hoofdlettergevoelig zijn, wat betekent dat `myVariable` en `myvariable` als verschillende variabelen worden beschouwd.

2. Begin met een letter of underscore: Een variabelenaam moet beginnen met een letter (a-z, A-Z) of een underscore-teken (_). Het is geen geldige syntaxis om te beginnen met een cijfer.

3. Geen speciale tekens of spaties: Je kunt geen speciale tekens zoals @, $, %, enz. gebruiken in een variabelenaam. Ook spaties zijn niet toegestaan. Als je een naam met meerdere woorden wilt gebruiken, kun je underscores gebruiken (bijv. `my_variable`) of de camelCase-notatie volgen (bv. `myVariable`).

4. Vermijd gereserveerde woorden: Je moet voorkomen dat je gereserveerde woorden of sleutelwoorden van Python gebruikt als variabelenamen. Bijvoorbeeld: `if`, `for`, `while`, `def`, enz. Deze woorden hebben een specifieke betekenis in de Python-syntax en worden gebruikt voor het uitvoeren van bepaalde acties. Als je ze als variabelenamen gebruikt, kan dit leiden tot syntaxisfouten.

5. Beschrijvend en betekenisvol: Het is een goede praktijk om variabelenamen te kiezen die beschrijvend en betekenisvol zijn. Geef je variabelen namen die de intentie en het doel van de opgeslagen waarde weergeven. Bijvoorbeeld: `count`, `total_amount`, `student_name`, enz. Dit maakt je code leesbaarder en gemakkelijker te begrijpen.

## Cheatsheet

### 1. Variabele toewijzen

```[Python]
variabele_naam = value
```
