# Half-Gammon 🎲

A console-based implementation of a simplified backgammon variant 
built in C++ and C. Players move checkers around the board according 
to dice rolls, blocking and hitting opponent pieces, with the goal 
of bearing off all checkers first.

## Gameplay
- Two players take turns rolling dice and moving checkers
- Move checkers the number of points shown on each die
- **Hit** an opponent's lone checker to send it to the bar
- A checker on the bar must re-enter before other moves can be made
- **Bear off** your checkers once all are in your home board
- First player to bear off all checkers wins

## Features
- Full two-player turn-based gameplay
- Dice roll simulation with valid move generation
- Hit and bar mechanics — knocked checkers must re-enter
- Bear-off logic when all checkers reach the home board
- Move validation — only legal moves accepted
- Clean ASCII board display updated after every turn
- Input handling for selecting checker and destination

## Board Display
```
 13 14 15 16 17 18    19 20 21 22 23 24
 |-O--O--O--------|-|-----------X--|
 |                |-|               |
 |-X--X--X--------|-|-----------O--|
 12 11 10  9  8  7     6  5  4  3  2  1
```

## Concepts Demonstrated
- Complex game state management in C/C++
- Multi-rule move validation logic
- Dice simulation and turn flow control
- Array and vector manipulation for board representation
- Mixed C and C++ programming
- Console-based UI rendering

## How to Run
```bash
g++ -o halfgammon main.cpp
./halfgammon
```

## Languages
- **C++** (69%) / **C** (31%)

---
*Built as part of CS coursework @ University of Illinois Chicago*
