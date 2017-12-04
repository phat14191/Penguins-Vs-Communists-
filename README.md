# Penguins-Vs-Communists

NodeJS Project way to deal with Objects/Associative Arrays, Constructors or "Classes", Callback functions. Deciding the fate of the Penguins or Communists through Javascript callbacks. 

## Screenshots
![Images](https://s3-us-west-1.amazonaws.com/phat14191/ComunistVSPenguins.png)

## Download and Run

1) git clone https://github.com/phat14191/Penguins-Vs-Communists-
2) cd Penguins-Vs-Communists-
3) node app.js 

## Detail Project

This project runs Penguins Vs Communists are located in [app.js](https://github.com/phat14191/Penguins-Vs-Communists-/blob/master/app.js) and are explained more fully below. 

##### ***Two Players:***

- Create two parties: "Penguins" and "Communists"  (Create a Javascript class and use the new keyword to instantiate the parties).
- Each party has a starting population of 1,000,000.

##### ***Flip a coin***

 - Random number between 1 and 2 to see which party attacks first (50% on hit or NONE)

##### ***Create a function called sendNuke(partyAttacking, onHit, onMiss) where:***

 - The first parameter party is the Javascript object of the party that will be attacked.
 - The second parameter onHit is a callback function that will be called if the attack is successful.
 - The third parameter onMiss is a callback function that will be called if the attack is unsuccessful.
 - the onHit and onMiss functions each take one parameter of type party (just forwarding the party you already passed into sendNuke).
 
##### ***Print messages in the callbacks that are appropriate:***

 - If the attack missed then it would log "The Communist/Penguins MISSED their nuke".

##### ***If an attack is successful:***

 - Print out initiate a random damage amount, and populations remaining.

##### ***After an attack is completed (or missed) the opposing party will initiate an attack:***

 - This process will repeat until one of the parties reaches a 0 population
 - Then will print out "The *** ***Communists/Penguins*** ***" is Won!!!
