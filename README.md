# EXP - 01 MDP REPRESENTATION

## AIM:
To represent a Markov Decision Process(MDP) problem in the following ways.

1) Text representation
2) Graphical representation
3) Python - Dictonary representation

## PROBLEM STATEMENT:

### Problem Description
In this case consider a frog as a agent.that frog jump the next and next leaf to reach the goal - (insects) 

### State Space

{B,A,C,D,E,F,G} -> {0,1,2,4,3,5,6}

* These are state to the frog to reach the goal

### Sample State

2 

### Action Space

* {0} -> LEFT
* {1} -> UP
* {2} -> RIGHT

### Sample Action

{1} -> UP

### Reward Function

* To reach goal ->+1(Reward) 
* Otherwise ->0

### Graphical Representation

<img width="637" alt="image" src="https://github.com/Monisha-11/mdp-representation/assets/93427240/a7595c00-5896-4532-9c60-0ac6713f5c9b">




## PYTHON REPRESENTATION:
```python

P = {

    0 : {
        0 : [(1.0 , 0 , 0.0 , False)],
        1 : [(1.0 , 0 , 0.0 , False)],
        2 : [(0.7 , 1 , 0.0 , False), (0.3 , 0 , 0.0 , False)]
    },

    1 : {
        0 : [(0.7 , 0 , 0.0 , False),(0.3 , 1 , 0.0 , False)],
        1 : [(0.7 , 4 , 0.0 , False),(0.3 , 1 , 0.0 , False)],
        2 : [(0.7 , 2 , 0.0 , False),(0.3 , 1 , 0.0 , False)]
    },

    2 : {
        0 : [(0.7 , 1 , 0.0 , False),(0.3 , 2 , 0.0 , False)],
        1 : [(1.0 , 2 , 0.0 , False)],
        2 : [(1.0 , 2 , 0.0 , False)]
    },

    3 : {
        0 : [(1.0 , 3 , 0.0 , False)],
        1 : [(1.0 , 3 , 0.0 , False)],
        2 : [(0.7 , 4 , 0.0 , False),(0.3 , 3 , 0.0 , False)]
    },
    4 : {
        0 : [(0.7 , 3 , 0.0 , False),(0.3 , 4 , 0.0 , False)],
        1 : [(0.7 , 6 , 1.0 , True),(0.3 , 4 , 0.0 , False)],
        2 : [(0.7 , 5 , 0.0 , False),(0.3 , 4 , 0.0 , False)]
    },
    5 : {
        0 : [(0.7 , 4 , 0.0 , False),(0.3 , 5 , 0.0 , False)],
        1 : [(1.0 , 5 , 0.0 , False)],
        2 : [(1.0 , 5 , 0.0 , False)]
    },
    6 : {
        0 : [(1.0 , 6 , 0.0 , True)],
        1 : [(1.0 , 6 , 0.0 , True)],
        2 : [(1.0 , 6 , 0.0 , True)]
    },
}

P

```
## OUTPUT:

<img width="459" alt="image" src="https://github.com/Monisha-11/mdp-representation/assets/93427240/31c5f9ab-a247-420d-b637-e618417bee1b">




## RESULT:
Thus a real world problem is represented as Markov Decision Problem in the following ways successfully:

Graphical Representation
Python Representation

