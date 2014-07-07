#Computational Thinking <img src="../../Resources/brain.png" width=50px alt="Tick Sheet">


##Instructions
For this computational thinking challenge you should attempt to find a answer to problem set below. The answer to the problem is only part of your response, ***how*** you found the answer is what matters.

Once you can explain the solution you might try to write a computer program to simulate or model the solution. It might even generalise the problem and provide solutions for ***similar*** problems.

##Grading
|Grade|What must I do?|
|-----|---------------|
|D|I will be able to provide an answer to the problem.|
|C|I will be able to provide an answer to the problem, including an explanation of the algorithm / process.|
|B|I will be able to provide a clear explanation of the algorithm I developed to solve to problem.|
|A/A*|I have been able to demonstrate my understanding of the solution to this problem and represented the algorithm using a computer program.|

##The Problem - Ferrying Soliders
####A detachment of **25** soliders need to cross a deep wide river, with no bridge in sight. They spot two boys playing around in a row boat near the shore. They notice two children playing in a rowboat by the shore.
![Ferrying soldiers](../../Resources/ferrying.png)
####The boat is so tiny, however, that it can only hold the two children *or* one of the soliders. How can the soliders get across the river and leave they children in joint posession of the boat? How many times does the boat need to pass from shore to shore in your solution?

###Rules:
- All 25 soliders must end up on the other side of the river.
- The boat can carry one child by themselves, both children or a single solider.
- At the end both children must be with the boat on either shore.

####How many trips from shore to shore must the boat take?
```
100
```
####Explain you algorithm here:
```
The 2 kids take the boat to the other side of the shore, and 1 child take the boat back leaving the other behind.
A soldier takes the boat to the other side and the kid with the soldier takes the boat back. This is repeated 25 times meaning a total of 100 trips to get all 25 soldiers to the other side of the shore with the kids in possesion of their boat.
```

##Extension
Can you represent the algorithm for this problem using a computer program (any language)?
eg you could show each step in the algorithm using text:

```
1.) 2 children take the boat to the shore.
2.) Take 1 child back.
3.) 1 soldier takes the boat to shore.
4.) 1 child takes the boat back to shore.
x 25 = 100 times   
```
    

For text based programs like python you should create a new file in you repository
![Add new](../../Resources/new.png)

For anything else (eg scratch), email you teacher with the file and say you've done so in the comments.
