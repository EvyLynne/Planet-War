# Planet-War
Project to practice Full Stack Java Programming
A small Object Oriented Full Stack project in Java.  
The goals of this project are to review and refresh:
Practical software design principles
Practial application of Java using the 4 principles of Object Oriented Coding:
  1. Encapsulation
  2. Inheritance
  3. Polymorphism
  4. Abstraction
  
Software Development Lifecycle
Agile Development

Requirements:
The planets in our solar system have taken sides in two teams and are trying to fight to win control over the Sun's energy.  This assumes all the planets are populated and have some resources.  I've set it up similar to the States voting for President in the USA.   

The Sun's luminosity is approximately 3.86 x 1026 watts of power radiated out into space. <br>[https://ag.tennessee.edu/solar/Pages/What%20Is%20Solar%20Energy/Sun%27s%20Energy.aspx#:~:text=The%20Sun%20releases%20an%20estimated,radius%20of%20approximately%2093%2C000%2C000%20miles.  ](https://www.sws.bom.gov.au/Educational/2/1/12)
Each planet has orbit, mass, diameter, gravity and population as minimal characteristics.  Some have optional satellite moon(s) and rings per https://en.wikipedia.org/wiki/Planet
and https://solarsystem.nasa.gov/planets/in-depth/  I added population to all planets. 

Since some of this is science fiction, I took the Earth's current population of 7.8 billion [https://www.worldometers.info/world-population/] and extrapolated populations for the remaining seven planets. I calculated the difference in percentage of the diameter and then mulitplied our population by the difference. 

Since Mercury and Neptune were so small, I gave them extra weapons to prevent repated loss from gameplay early on.  Since Jupiter and Saturn were much larger, I underpopulated them so they wouldn't always dominate gameplay.  I start each planet with a full arsenal of torpedos and strength.  To keep this project simple, each torpedo kills 1 billion people and a planet is considered lost when it is out of torpedoes or lost half of its population or more.  In the event of a tie, the system autmoatically rolls a random number and assigns a winner. 
To keep the math simple, I flattened out the solar system onto Euclidean space so that the distance formula between any two planets is the distance between two points. D = SQRT [( y2 - y1 ) squared + ( x2 - x1 ) squared].  The unit of measure for planetary distance from the sun is Astronomical Units to avoid memory overflow.  To further simplify things, I used the distance from the sun as the orbit and did not take into account the differences in orbit. 

Basic gameplay:

0. Computer randomly places planets in their orbits around sun.
1. Computer randomly assigns planets to two teams.  Player can reassign or accept default setting.
2. Player can chose starting team or allow computer to randomly start. 
3. Distance from starting planet to other planets is calculated and closest planet is target. 
4. If the torpedo hits the sun, it is destroyed and the planet that fired loses the torpedo; else if the torpedo hits the target 1 billion people are killed. 
5. If the target drops to half the original population or less, it is removed from gameplay. 
6. Game continues until one team loses all planets. 


I used my college textbook, Software Engineering 10th edition by Ian Sommerville starting at page 198 for design guidelines for a software system. I downloaded a free trial copy of SmartDraw 2020 to create the diagrams. 


Online resources used while researching this: 

Geeks For Geeks

Wikipedia Design Patterns - Patterns by Type https://en.wikipedia.org/wiki/Design_Patterns#Patterns_by_type
W3Schools Java Language Reference
UML Class Diagram Tutorial: https://www.visual-paradigm.com/guide/uml-unified-modeling-language/uml-class-diagram-tutorial/

