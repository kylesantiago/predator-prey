## WHAT IS IT?

This model explores the predator prey ecosystem. 

## HOW IT WORKS

This model contains 2 agents, Books and Scholars. 

In this model, books have come alive and are looking for pages scattered in the environment to maintain their energy levels. Scholars are tasked with hunting down these books and reading them to sedate the books and increase their energy to read more books. Both agents lose energey when moving, and when either run out of energy they disappear. Additionally, each agent has its own independent reproduction rate to maintain agent population. 

## HOW TO USE IT

1. Adjust slider parameters 
2. Press the SETUP button to initialize the simulation
3. Press the Go button to begin the simulation
4. Monitor population sizes and plot to examine population fluctuation

Parameters: 
PAGE-RESPAWN-TIME: The time it takes for a page to spawn into the environment
NUM-BOOKS: The initial amount of living books
NUM-SCHOLARS: The initial amount of scholars
BOOK-START-ENERGY: The initial amount of energy for each living book
SCHOLAR-START-ENERGY: The initial amount of energy for each scholar
BOOK-ENERGY-GAIN: The amount of energy gained by a living book for eating a page
SCHOLAR-ENERGY-GAIN: The amount of energy gained by a scholar for reading a book
BOOK-REP-RATE: The probability of a living book reproducing
SCHOLAR-REP-RATE: The probability of a scholar reproducing

If there are no more books or scholars the simulation stops.
## THINGS TO NOTICE

Notice that though the amount of living books dominate the scholars, as time progresses eventually scholars population will increase and attempt to catch up to the living book population or dominate it. 

## THINGS TO TRY

Try modifying the parameters to see how the behavior will change.

## EXTENDING THE MODEL

Additional parameters and more rules could drastically affect the model and show a more accurate predator and prey ecosystem

## NETLOGO FEATURES

Notice the use of <breeds>-here with collects all of the turtles within a caller's area

## RELATED MODELS

Look at Wolf Sheep Predation for another model of similar interaction

## CREDITS AND REFERENCES

Wilensky, U. (1997). NetLogo Wolf Sheep Predation model. http://ccl.northwestern.edu/netlogo/models/WolfSheepPredation. Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.
