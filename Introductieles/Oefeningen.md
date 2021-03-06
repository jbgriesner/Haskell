Oefeningen introductieles
=========================

Als je vast zit, vraag zeker hulp!

Getting started
---------------

Zet volgende code bovenaan, om een aantal conflicten te

    import qualified Prelude

Implementeer volgende functies:

    inc		:: Int -> Int

````inc```` geeft het gegeven getal plus 1.


    double		:: Int -> Int

````double```` geeft het dubbel van de parameter.

    giveOne	:: a -> Int

````giveOne```` neemt een willekeurige waarde en geeft '1' terug.

    const	:: a -> b -> a

````const```` geeft altijd het eerste argument terug, en doet niets met het tweede argument.


### Recursie

Implementeer ````faculteit :: Int -> Int````

Implementeer ````fib :: Int -> Int```` die het ````n````-de fibonacci getal teruggeeft

### Higher order

Implementeer ````doTwice````

Lijsten
-------

Implementeer een eigen lijst zoals in de slides.

Merk op: Haskell weet niet dat je die lijst mag afprinten. Zet ````deriving Show```` achter je eigen data definities ```` data Lijst a = .... | .... deriving Show````

Implementeer ````mx```` die het grootste element uit een lijst van ````Int````s haalt.
	Je mag hiervoor if gebruiken:

    if voorwaarde then expressie else expressie

Implementeer ````som```` die alle getallen van een lijst van ````Int````s optelt.

Implementeer ````lengte````

Implementeer ````onEach````

Implementeer ````lengte'````, die de lengte van de lijst berekend. Hierbij gebruik je geen recursie, maar ````som````, ````map```` en ````giveOne````. (Functienamen mogen single quotes bevatten)

Implementeer ````reverse````, die een lijst omdraait. Het kan handig zijn om eerst een functie te maken die een waarde achteraan de lijst toevoegt.

Klaar?
------

Vond je de les interessant?

Zoveel te beter! We geven (indien genoeg interesse) een volledige lessenreeks in het tweede semester.
Toon alvast je interesse hier: [feedback haskell](http://goo.gl/forms/cjqiEPni7y)
