# 42 fillit

![Score](score.png)
***
### Challenge

**Algorithms Practice - Fit tetris pieces into the smallest square possible.**

## How to run

make; ./fillit test_tetros.txt`

## What Fillit Does:
Fillit recieves a map text file like this one with pieces.

![Valid Map](https://github.com/Jemmeh/42-Fillit/blob/master/WorkFiles/ExplainationImages/ExampleMapFile.png?raw=true)

It finds the smallest possible square the pieces can be arranged in and prints out the square like this:

![SolvedSquare](https://github.com/Jemmeh/42-Fillit/blob/master/WorkFiles/ExplainationImages/ExampleSolution.png?raw=true)

## Testing
You can run two test documents **test_tetros.txt** and **test_tetros2.txt**(or write your own).

First of all run command: `make`
It will compile all necessary files.

Then run any test you want like this: `./fillit [test_name]`

**test_testros.txt** should show:
```console
AA.C.
AA.C.
BB.C.
.BBC.
DDDD.
```
And **test_tetros2.txt**:
```console
AABBCCDDEE
AABBCCDDEE
FFGGHHIIJJ
FFGGHHIIJJ
KKLLMMNNOO
KKLLMMNNOO
PPQQRRSSTT
PPQQRRSSTT
UUVVWWXXYY
UUVVWWXXYY
```

## Speed Requirements
This is not on the PDF but is a requirement by the grading scale.

`time ./fillit test1.prm`

    must execute <= 1 second

`time ./fillit test7.prm`

    30 seconds+ -> 0 pts
    20-30 seconds -> 1 pt
    10-20 seconds -> 2 pt
    5-10 seconds -> 3pt
    1-5 seconds -> 4pt
    < 1 second -> 5 pt

Ours scores 0.00s in both cases so we got max score on this part.

Special thanks to my partner mcathery
