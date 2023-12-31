># Grupparbete: Datalogiskt tänkande 
>## Grupp: Furious Pirates. 
>>Sandra, Jonas, Erik och Kim

FigJam länk:
https://www.figma.com/file/IuELQRMXQaMmgd1nkOjPxP/Furious-Pirates?type=whiteboard&node-id=0%3A1&t=Sel3mr9yV6kLony3-1

### Decompisition:
Vi påbörjade arbetet med Decomposition. Vi brainstormade och ritade upp på whiteboard tavla först, för att få en bättre översikt över de olika momenten innan vi tog fram FigJam ...

Under det här momentet gjorde vi egna antaganden, eftersom det saknades viktiga funktioner i designen som vi utgick från. Det var antaganden som vi ansåg vara nödvändiga för en välfungerade applikation. Vi antog exempelvis att det fanns ett lagersaldo, hur flödet i appen ser ut vid en beställning, att man kan lägga till och ta bort produkter, vilka betalningsmetoder som finns att tillgå, orderbekräftelse via mail och hur man navigerar i applikationen.


**De huvudkategorier vi definierade var**: 

- Design
- Produkter
- Användarprofil
- Order
- Betalningshantering
- Varukorg

### Pattern Recognition:

När vi sen hade en helhetsbild över appen, så började vi identifiera mönster.

**Vi kom fram till att:**
- Font och färgtema används konsekvent i appen.
- Användning av databas för att hantera variabler och information.
- Burgarmeny-ikonen är placerad på samma position på alla sidor för kontinuitet.
- Kontroller av information i databasen för att säkerställa korrekthet och tillförlitlighet.


Vi antog att det användes databaser för att hantera information om olika variabler och att det krävdes formulärvalidering.

### Abstraction:

Syftet med denna delprocess är att lyfta fram de mest relevanta delarna och få ett fungerande flöde för appens funktion. De mest relevanta delarna, ansåg vi vara:

**Användarprofil:**

- Fast det inte finns krav på inloggning, ansåg vi att en användarprofil möjliggör för kunden att utnyttja appens alla funktioner och göra det smidigare vid beställning.

**Produkter:**

- Appens funktion är att sälja kaffe, och då måste det finnas kaffe att sälja. Vidare så bör kunden också få information om de olika produktutbuden, huruvida de finns tillgängliga (lagerstatus), samt vad de kostar. 


**Varukorg:**

- Vi ansåg det var viktigt att ge all information om pris och produktantal för att sedan bekräfta beställningen. Här antog vi att kunden kan lägga till och ta bort produkter, samt att kunden skickas till en betalningssida när kunden bekräftar sin beställning genom att trycka på “Take My Money”-knappen. 

**Betalhantering:**

- Säkerställa korrekt betalning och tillförse kunden med olika och säkra betalningsalternativ. Här antog vi de olika betalningsalternativen som bör finnas tillgängliga, exempelvis Swish och Kortbetalning.

**Order:**

- Vidare ansåg vi att det är viktigt för kunden att få information om sin order. Vi antog då att kunden får en orderbekräftelse via e-post. Att kunden får information om var ordern skickas till (leveransadress), att kunden får information om var ordern befinner sig (platsinformation), samt hur lång tid det tar för ordern att komma.

### Algorithm Design:

Ett flödesschema är ett bra verktyg för att planera, visualisera, dokumentera och förbättra processer. I detta fall, processen att beställa kaffe via AirBeans appen. Flödesschemat hjälpte oss få en överblick över processen samt att identifiera och förebygga flaskhalsar eller problem, exempelvis att användaren fastnar och inte kan ta sig tillbaka i appen. 

**Vi gjorde några antaganden innan vi skapade flödesschemat, exempelvis:**

- Grön Air Bean sida är en laddnings sida som försvinner automatiskt när sidan har laddats.
- Efter att sidan har laddats kommer man till meny sidan med produkter. 



Vi avslutade med att aväga om vi skulle fördjupa oss mer i Decomposition, men vi kom fram till att vi hade fått med det viktigaste. Vi tycker att det har varit lärorik process som vi säkert får stor använding av i framtiden!



**Övriga antaganden:**

Air Bean-sidan fungerar som en laddningssida som automatiskt försvinner när sidan har laddats klart.

- Efter laddning tar användaren sig till meny-sidan med produkter.
- Att trycka på plus-knappen placerar produkten i varukorgen.
- Varukorgen visas genom att trycka på en ikon och få en dropdown-meny.
- Burgarmeny ger tillgång till menyn på den aktuella sidan.
- Om användaren inte är inloggad finns knappar i burgarmenyn för att skapa eller logga in.
- Vi har antagit hur man tar sig till inloggningssidan.
- Vi har antagit hur man navigerar sig inuti appen.
- Vi har antagit att man inte kan välja storlek på produkten
