# Planet-War
Project to practice Full Stack Java Programming
Upon passing the first round of interviewing at Fidelity, I decided to put the interviewer's recommendations to practical use and write a small Object Oriented Full Stack project in Java to prepare for my second interview.  The goals of this project are to review and refresh:
Practical software design principles
Practial application of Java using the 4 principles of Object Oriented Coding:
  1. Encapsulation
  2. Inheritance
  3. Polymorphism
  4. Abstraction

Requirements:
This idea is my own. The planets in our solar system have taken sides in two teams and are trying to fight to win control over the Sun's energy.  This assumes all the planets are populated and have some resources.  I've set it up similar to the States voting for President in the USA.  I did a little research to make it fun.  The Sun emits 384.6 yotta watts (3846 * 1026 watts) of energy [https://ag.tennessee.edu/solar/Pages/What%20Is%20Solar%20Energy/Sun%27s%20Energy.aspx#:~:text=The%20Sun%20releases%20an%20estimated,radius%20of%20approximately%2093%2C000%2C000%20miles.].  Each planet has orbit, mass, diameter, gravity and population as minimal characteristics.  Some have optional satellite moon(s) and rings. Since some of this is science fiction, I took the Earth's current population of 7.8 billion [https://www.worldometers.info/world-population/] and extrapolated. I gave Mercury extra weapons to get it a better chance at survival.  I underpopulated Jupiter so it wouldn't always dominate.  I start each planet with a full arsenal of torpedos and strength.  To keep this project simple, each torpedo kills 1 billion people and a planet is considered lost when it is out of torpedoes or lost half of its population or more.  In the event of a tie, the system autmoatically rolls a random number and assigns a winner. 
