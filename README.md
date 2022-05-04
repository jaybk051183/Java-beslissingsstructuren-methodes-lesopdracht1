## Inleiding
Welkom bij de eerste huiswerkopdracht die jullie gaan maken voor de Backend leerlijn. Je hebt als het goed is de hoofdstukken 1 t/m 2.5 gelezen en de eerste les van de cursus Java gevolgd. In deze opdracht ga je oefenen met wat je tot nu geleerd hebt over beslissingsstructuren en methodes. 

## Opzetten van een nieuw Java project

1. Open IntelliJ op je computer.

2. Kies rechts bovenin voor 'New project'.

3. Op het volgende scherm zie je linksboven dat 'Java' blauw geselecteerd is. Daar klik je op 'Next'.

4. Op het volgende scherm hoeven we niks te selecteren en kunnen we gewoon op 'Next' klikken.

5. Op het volgende scherm kunnen we een naam meegeven aan het project. Kies altijd een beschrijvende naam die iets zegt over je project zodat je ook weet wat erin staat. Bijvoorbeeld "javaOpdracht1".

6. Klik daarna op 'Finish'. Gefeliciteerd! Je hebt zojuist je eerste project aangemaakt.

## Opdrachtbeschrijving

Maak in het nieuwe Java project dat je hebt gemaakt een main klasse en een `public static void` main methode. Maak daarnaast ook de volgende methodes:
- hello()
- positiveOrNegative(int number)
- postiveOrZeroOrNegativ(int number)
- bartender(String name)
- sum(int number1, int number2)

Maak de volgende variabelen aan in de main methode:
- int number
- int number1
- int number2
- String name

Het gedrag van de methoden is als volgt: 
- De hello-methode print de regel "Hello, world!";
- De positiveOrNegative-methode print aan de hand van een `if else` statement "This number is positive!" of "This number is negative!";
- De positiveOrZeroOrNegative-methode print aan de hand van een `if else if else` statement "This number is positive!", "This number is zero!" of "This number is - negative!";
- De bartender-methode print aan de hand van een `switch` statement, het drankje dat deze persoon graag drinkt;
- De sum-methode print de uitkomst van de twee nummers die bij elkaar zijn opgeteld.

De waarde van number is 6.
De waarde van number1 is 4.
De waarde van number2 is 20.
De waarde van name is Henk.

Roep alle methodes aan vanuit de main methode, verander de waardes en kijk wat eruit komt als je de waardes aanpast en opnieuw draait. 

![Drinks](./assets/drankjes.jpg)


## Randvoorwaarden
De opdracht moet voldoen aan de volgende voorwaarden:

- minimaal 4 variabelen
- minimaal 5 methodes
- 1 if/else statement
- 1 if/else if/else statement
- 1 switch statement


## Stappenplan
Let op: het is uitdagender om jouw eigen stappenplan te maken. Als je niet zo goed weet waar je moet beginnen, kun je onderstaand stappenplan gebruiken.

1. Maak een nieuw project aan in IntelliJ.

2. Maak een nieuwe klasse aan genaamd  'main'. Doe dit door met de rechter muisknop op de map 'SRC' te klikken, vervolgens klik je op 'New' en dan op 'Java klasse'. 

3. Maak een `static void main` methode aan.

4. Maak in de `static void main` methode de variabelen aan die hierboven genoemd zijn met de juiste waarden. 

5. Maak na de `}` van de `static void main` methode een nieuwe static void methode met de naam 'hello'. Laat deze methode een regel printen door System.out.println te gebruiken. Kijk hierboven voor de juiste tekst. Deze methode krijgt geen variabelen mee gestuurd. 

6. Roep de `hello` methode aan in de `static void main` methode. Laat nu de applicatie draaien door op de play-knop in de goot van IntelliJ te drukken.

7. Maak een static void mehode aan met de naam 'positiveOrNegative' en geef deze de juiste parameters mee. Zet in deze methode een `if else` statement. De voorwaarde van de if is (number > 0). Bij de if moet de methode de tekst: "This number is positive!" printen. Bij de else mag de tekst: "This number is negative!".

8. Roep deze methode aan in de `static void main` methode en geef de juiste parameter mee. Laat de applicatie weer draaien door op de play-knop te drukken. 

9. Verander de waarde van number naar -6 en draai de applicatie opnieuw. Wat is er nu veranderd? En wat als het number de waarde 0 heeft? Klopt dit?

10. Maak een nieuwe static void methode aan genaamd 'positiveOrZeroOrNegative' en geef deze de juiste attributen mee. Plaats in deze methode een `if else if else` statement. Deze lijkt veel op de if else statement van positiveOrNegative methode, echter staat er tussen de if en de else nog een else if met de volgende voorwaarde: (number == 0) {System.out.println("This number is zero!}. 

11. Roep ook deze methode aan vanuit de `static void main` methode en geef ook hier de juiste variabele aan mee.

11. Maak een nieuwe static void methode genaamd bartender en geef deze de juiste parameter mee. Gebruik in deze methode de switch methode om aan de hand van de string name het drankje van verschillende personen te printen. 

12. Roep ook deze methode aan vanuit de `static void main` methode en speel met verschillende namen die je in de switch cases hebt gezet. 

13. Maak nog een static void methode aan genaamd 'sum' en geef deze de juiste variabelen mee. Laat deze methode de volgende tekst printen: "number1 summed by number2 = 24".

14. Roep deze methode ook aan in de `static void main` methode en speel met verschillende waardes.
