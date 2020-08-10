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

Special thanks to my partner mcathery
