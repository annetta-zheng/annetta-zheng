## Welcome to My Pages for CS/DS Projects
* Placeholder for Table of Content (Must not be removed) 
* Blocks Puzzle Game [Blocks Code](https://github.com/annetta-zheng/Blocks)
{:toc}


### Project - Blocks Puzzle Game
[Blocks Code](https://github.com/annetta-zheng/Blocks)

[Demo Game] (https://www.cbc.ca/kidscbc2/content/games/blocks-puzzle/index.html)

![image](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/proj/proj0/img/figure1.png)
![image](https://user-images.githubusercontent.com/67286396/157542546-95e9e541-91c9-4b81-9908-22c476265729.png)        


### Project - Enigma Machine
[Enigma Code](https://github.com/annetta-zheng/enigma)

For OOP, Data Structures in Java.
    
   The Settings Line and Input: 
   ```
      * B III II I maa (az) (mn)
      asb 
   ```
    
   Output: 
    ```
      wtt
    ```
   
   Configuration: 
```
    abcdefghijklmnopqrstuvwxyz
    4 3
    I Ma     (wordle) (is) (fun)
    II Mb    (tears) (boing) (lucky)
    III Mm   (quack) (froze) (twins) (glyph)
    B R      (az) (by) (cx) (dw) (ev) (fu)
             (gt) (hs) (ir) (jq) (kp) (lo) (mn)
```             

### Project - Ataxx Game
[Ataxx Code](https://github.com/annetta-zheng/Ataxx)

Minmax algorithm, alpha-bata pruning.

At the beginning of the game, we start with pieces in all four corners:

![image](https://user-images.githubusercontent.com/67286396/162055039-29887726-605e-4cf1-a4e8-524502033996.png)

There are two possible kinds of moves:
1. Extending - you can extend from a piece of your own color by laying down a new piece of your color in an empty square next to that existing piece (horizontally, vertically, or diagonally).
2. Jumping - you can jump by moving a piece of your own color to an empty, non-adjacent square that is no more than two rows and no more than two columns distant.
![image](https://user-images.githubusercontent.com/67286396/162054986-8001f120-07af-47fa-a00d-855faa3fb8fb.png)

To make things even more interesting, you can place a set of blocks symmetrically about the center of the board before playing. These are pre-filled squares that may never be moved to (the blocks themselves never move). Setting blocks is only possible at the start of the game. The illustration below is an example of a starting configuration with 10 blocks. Each block is always reflected across the middle row and the middle column. In other words, there is symmetry both horizontally and vertically for any block that is placed. No block may be placed in the four corner squares, since the initial configuration has pieces there.
![image](https://user-images.githubusercontent.com/67286396/162054882-7bc8ccb2-7356-49ce-a2c7-e528a48ab390.png)
