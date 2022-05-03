# Social Intranet

Je gaat starten met een uitbreiding op een bestaande social intranet applicatie.
Jouw uitbreiding gaat als losse applicatie, door middel van een HTTP API, ontsloten worden in een reeds bestaande applicatie.  
De bedoeling van het nieuwe systeem is dat je als gebruiker berichten kan publiceren. Andere gebruikers kunnen deze berichten weer ophalen. Wanneer een bericht wordt geplaatst moet iedereen daarvan per e-mail op de hoogte worden gesteld. Maar niet elke gebruiker heeft hier behoefte aan. Elke gebruiker heeft zo zijn eigen voorkeur of deze de e-mail wilt ontvangen. De persoon die het bericht heeft toegevoegd krijgt nooit een notificatie.

## De opdracht
Start een nieuwe Symfony applicatie en leg een HTTP API aan om berichten te plaatsen en weer op te halen. Je bent volledig vrij hoe deze API eruit ziet.
Laat in code zien hoe je van plan bent om te gaan met het versturen van e-mails naar de andere gebruikers. Je hoeft uiteraard niet daadwerkelijk e-mails te versturen. Het is afdoende als in de code duidelijk wordt waar je dit uiteindelijk wilt doen.
Ga ervan uit dat je eigen applicatie een lijst van gebruikers bezit met daarin de persoonlijke voorkeur of deze gebruiker een e-mail wilt ontvangen.
Daar waar mogelijk is je code voorzien van unit en/of behaviour tests.

**Acceptatiecriteria**
* Een bericht heeft maximaal 500 karakters
* Een gebruiker dat een bericht aanmaakt krijgt hier zelf nooit een notificatie van, ook al staat dat wel zo ingesteld in het profiel.
* Het moet mogelijk zijn om bij een gebruiker aan te geven dat deze maar 1 maal per uur een bericht mag plaatsen.
* Er is geen UI, alle communicatie gaat via een API.

**Nice to have**
* In een bericht kan je iemand noemen met een "@" notatie. Voorbeeld: Zodra gebruiker A een bericht plaatst met de tekst "Hallo @gebruikerB" dan krijgt gebruiker B daar een e-mail van waarbij de instelling in het profiel wordt genegeerd. Deze gebruiker moet dus altijd bericht krijgen.

## Wijze van inleveren
Maak een aparte (prive) repository en stuur ons de gegevens om de code in te zien.
