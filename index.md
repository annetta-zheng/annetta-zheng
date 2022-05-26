## Welcome to My Pages for Projects

### Catalogue
#### Python
- [Reviews Sentiment Analyzer](#Reviews-Sentiment-Analyzer)
#### Java
- [Blocks Puzzle Game](#Blocks-Game)
- [Enigma Machine](#Enigma-Machine)
- [Ataxx Game](#Ataxx-Game)
- [Gitlet](#Gitlet)

------------------------------
### Reviews Sentiment Analyzer
[Sentiment Analyzer Code](https://github.com/annetta-zheng/sentiment_analysis)

* Results:
Accuracy on the test set using the original dictionary: 80.20%
Accuracy on the test set using the dictionary with stop words removed: 80.80%

For the perceptron algorithm: best combination of T = 25, with validation accuracy = 79.40%
![Figure_4](https://user-images.githubusercontent.com/67286396/170519190-2d1c8fb1-4c49-4dd1-a3b9-6c594bce2842.png)

For the average perceptron algorithm: best combination of T = 25, with validation accuracy = 80.00%
![Figure_5](https://user-images.githubusercontent.com/67286396/170519252-46f6b01b-04f5-49e2-ae0c-9fe2f4b33f7f.png)

For the pegasos algorithm: best combination of T = 25 \lambda = 0.01, with validation accuracy = 80.60%
![Figure_6](https://user-images.githubusercontent.com/67286396/170519444-18c2d7d5-2fbd-47d2-a296-e35c39b1bf3d.png)
![Figure_7](https://user-images.githubusercontent.com/67286396/170519453-ef692e96-dd75-4c04-a340-a28d0762a820.png)

------------------------------
### Blocks Game
[Blocks Puzzle Game Code](https://github.com/annetta-zheng/Blocks)

[Demo Game] (https://www.cbc.ca/kidscbc2/content/games/blocks-puzzle/index.html)

![image](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/proj/proj0/img/figure1.png)
![image](https://user-images.githubusercontent.com/67286396/157542546-95e9e541-91c9-4b81-9908-22c476265729.png)  

------------------------------
### Enigma Machine
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

------------------------------

### Ataxx Game
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


------------------------------

### Gitlet
[Gitlet Code](https://github.com/annetta-zheng/Gitlet)

A [version-control system](https://gitlet.cs61bee.org) is essentially a backup system for related collections of files. 

The main functionality that Gitlet supports is:
1. Saving the contents of entire directories of files. In Gitlet, this is called committing, and the saved contents themselves are called commits.
2. Restoring a version of one or more files or entire commits. In Gitlet, this is called checking out those files or that commit.
3. Viewing the history of your backups. In Gitlet, you view this history in something called the log.
4. Maintaining related sequences of commits, called branches.
5. Merging changes made in one branch into another.
6. Going remote, allowing collaboration with other people over the internet. 

##### Internal Structure
![image](https://gitlet.cs61bee.org/image/commits-and-blobs.png)
![image](https://gitlet.cs61bee.org/image/split_point.png)

##### Commands:
By starting up the program `java gitlet.Main init`, it will create a repo directory and an initial commit through the command init().
Based on the command run, structure of files will be saved.

```
1. java gitlet.Main add [file name]
2. java gitlet.Main commit [message]
3. java gitlet.Main rm [file name]
4. java gitlet.Main log
5. java gitlet.Main global-log
6. java gitlet.Main find [commit message]
7. java gitlet.Main status
8. java gitlet.Main checkout -- [file name]
9. java gitlet.Main checkout [commit id] -- [file name]
10. java gitlet.Main checkout [branch name]
11. java gitlet.Main branch [branch name]
12. java gitlet.Main rm-branch [branch name]
13. java gitlet.Main reset [commit id]
14. java gitlet.Main merge [branch name]
```

##### Sample Outputs:
```java gitlet.Main log```

    ```
    ===
     commit a0da1ea5a15ab613bf9961fd86f010cf74c7ee48
     Date: Thu Nov 9 20:00:05 2017 -0800
     A commit message.

     ===
     commit 3e8bf1d794ca2e9ef8a4007275acf3751c7170ff
     Date: Thu Nov 9 17:01:33 2017 -0800
     Another commit message.

     ===
     commit e881c9575d180a215d1a636545b8fd9abfb1d2bb
     Date: Wed Dec 31 16:00:00 1969 -0800
     initial commit
     ```
     
```java gitlet.Main status```

  ```
  === Branches ===
  *master
  other-branch

  === Staged Files ===
  wug.txt
  wug2.txt

  === Removed Files ===
  goodbye.txt

  === Modifications Not Staged For Commit ===
  junk.txt (deleted)
  wug3.txt (modified)

  === Untracked Files ===
  random.stuff
  ```

##### Edge Case for Merge:
1. Conflict Files
Any files modified in different ways in the current and given branches are in conflict. “Modified in different ways” can mean that the contents of both are changed and different from other, or the contents of one are changed and the other file is deleted, or the file was absent at the split point and has different contents in the given and current branches. In this case, replace the contents of the conflicted file with
  
  ```
  <<<<<<< HEAD
  contents of file in current branch
  =======
  contents of file in given branch
  >>>>>>>
  ```

Once files have been updated according to the above, and the split point was not the current branch or the given branch, merge automatically commits with the log message Merged [given branch name] into [current branch name]. Then, if the merge encountered a conflict, print the message Encountered a merge conflict. on the terminal (not the log). Merge commits differ from other commits: they record as parents both the head of the current branch (called the first parent) and the head of the branch given on the command line to be merged in.

2. Criss-cross Merges
![image](https://user-images.githubusercontent.com/67286396/167206258-25b6e353-5ca9-4052-8121-190b188be1dd.png)

 - Choose the candidate split point that is closest to the head of the current branch (that is, is reachable by following the fewest parent pointers along some path). 
 - If multiple candidates are at the same closest distance, choose any one of them as the split point. (We will make sure that this only happens in our test cases when the resulting merge commit is the same with any of the closest choices.)
