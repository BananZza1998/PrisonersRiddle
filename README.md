# PrisonersRiddle
Here I try to simulate the solution of the 100 prisoners problem (spoiler: strategy works!)

Repo content:
1. 100prisoners.ipynb - main code
2. https://en.wikipedia.org/wiki/100_prisoners_problem - link to the problem wiki page

The problem Statement

Setup:
100 prisoners with numbers written on their suits {1,...,100}  
100 boxes with number labels {1,...,100}  
100 papers of numbers {1,...,100}  

Prisoners are standing in front of the door. The room that is on the other side of the door contains 100 labeled boxes, each containing a randomly assigned
paper with a number written on it (each number is unique).  

The GOAL of each prisoner is to find a box with a paper that has a similar number to the one that is on his suit. 50 trials are given to him. 

No communication among prsioners is allowed once the game begins.  

Given that, the expected probability to find a desired number is p = 0.5. 

The game continues until the last prisoner leaves the room. 
 
There are only 2 outcomes of the game:
1. WIN - all the prisoners managed to find their numbers
2. LOSE - at least one of them failed

Therefore, p(WIN) = (0.5)^100, which sounds like it is impossible to win.  

HOWEVER  

There is a certain strategy, which increases the expected probability of winning from that small number to 0.31

More about this strategy could be found on the wikipedia page (![link](https://en.wikipedia.org/wiki/100_prisoners_problem) in the repo content)
Or in this video, which I originnaly saw it from (![video](https://www.youtube.com/watch?v=iSNsgj1OCLA))


Check the code for the results of simulation

