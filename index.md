## Welcome to My Page

### Contact
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555)](https://www.linkedin.com/in/junwen-zheng-789569195/ "My LinkedIn")

[![Email](https://user-images.githubusercontent.com/67286396/235269612-5f168df1-48a2-4f1a-8c84-5b24d4ede83a.png)](mailto:annetta@berkeley.edu)

______________________________

### Catalogue

#### Certifications
- [Amazon QuickSight](#Amazon)
- [Meta Data Engineer](#Meta)

#### Deep Learning/Machine Learning
- [Sentiment Analysis and Music Recommendations Systems](#Sentiment-Analysis-and-Music-Recommendations-Systems)
- [Reviews Sentiment Analyzer](#Reviews-Sentiment-Analyzer)
- [Local Frog Predictor](#Local-Frog-Predictor)

#### Software Engineering 
###### Python
- [Flask Blog Post Web App](#flask-blog-post-web-app)
- [RESTful Messenger Web App](#RESTful-messenger-web-app)

###### Java
- [Gitlet File System](#Gitlet)
- [Blocks Puzzle Game](#Blocks-Game)
- [Enigma Machine](#Enigma-Machine)
- [Ataxx Game](#Ataxx-Game)

###### JavaScript
- [Full Stack Blog App with React, Node.js, Express, MySQL](#Blog-App)



______________________________
### Certifications

##### Amazon
- [x] [AWS - Introduction to Amazon Quicksight.pdf](https://github.com/annetta-zheng/annetta/files/11357701/137_3_3110879_1678134335_AWS.Course.Completion.Certificate.pdf)
- [x] [AWS - Visualizing with Quicksight.pdf](https://github.com/annetta-zheng/annetta/files/11357703/41_3_3110879_1678142217_AWS.Course.Completion.Certificate.pdf)

##### Meta
- [x] [Meta - Introduction to Data Engineer.pdf](https://github.com/annetta-zheng/annetta/files/11357723/Coursera.6APZDH8JTYRQ.pdf)


------------------------------

______________________________

### Blog App
[Code](https://github.com/annetta-zheng/Full-Stack-Blog-App-with-React-Node.js-MySQL)

This is a for a full stack Blog Application using React components on the front end, with a CRUD Application using NodeJS + Express + MySQL on the back end.
<details>
      <summary>Features</summary>
       * One of the key features of this application is the ability for users to register and create their own blog posts. Users can write, update, and delete their blog posts powered by a MySQL database. 
      * The application also includes features such as authentication and authorization to ensure that only authorized users can create, update, and delete blog posts. 
      * Another important feature is customizing, users can view the posts filtered by categories and get posts recommendation within the same category. 
      * The React components used in the front-end include a variety of UI elements and the components are designed to be reusable, allowing developers to build complex interfaces using a combination of simple components and allowing user to post and edit a blog with rich text editors and pictures. 
      * The web app is also designed to be responsive, adapting to different screen sizes and orientations.
</details>      

<img width="582" alt="image" src="https://user-images.githubusercontent.com/67286396/234439050-2da14148-ae4c-4d76-a797-e7a0ddfe6473.png">

<p align="right">^<a href="#Contact">Back to Top</a></p>

------------------------------

### flask blog post web app
[Code](https://github.com/annetta-zheng/flask-blog-post-web-app)
A Flask landing page with SQLAlchemy displaying blog posts and allowing users to login and register.
<img width="1000" alt="image" src="https://user-images.githubusercontent.com/67286396/199391099-ee012a6b-7faa-4627-896c-4beaaa1e6735.png">

<p align="right">^<a href="#Contact">Back to Top</a></p>

------------------------------
### RESTful messenger web app
[Code](https://github.com/annetta-zheng/web-messenger-app)
RESTful API Project with Redis Nameko.


<p align="right">^<a href="#Contact">Back to Top</a></p>

------------------------------

### Sentiment Analysis and Music Recommendations Systems	
[Code](https://github.com/annetta-zheng/music-recommender)

Sentiment Analysis and Music Recommendations Systems Description: a review-based recommendation system with natural language processing (NLP) and Collaborative Filtering on 1.5M review data and 75k music meta data, utilizing Python via keras framework on an AWS EC2 instance.

1. Trained a convolutional neural network (CNN) for Sentiment Analysis on the review texts classifying the reviews as positive and negative, summarized keyword using NLTK, visualized word embeddings, and gained 91.4% test accuracy.

      <img width="769" alt="image" src="https://user-images.githubusercontent.com/67286396/204599514-0c6ab305-e115-403f-bf68-8135e06a339b.png">

      The most significant words in review texts:
<img width="769" alt="image" src="https://user-images.githubusercontent.com/67286396/204599154-f5964ddd-9138-49c9-8e1b-fd5b70d0f30f.png">

      The most significant words in summary texts:
<img width="769" alt="image" src="https://user-images.githubusercontent.com/67286396/204599389-b72f1da1-b877-4eab-88c0-74d2500b6908.png">

2. Trained a stacked Autoencoder with SGD on tokenized and embedded text matrix for dimensionality reduction.
      <img width="432" alt="image" src="https://user-images.githubusercontent.com/67286396/204599574-3ae71217-c4e7-40e4-a336-ee15429344c3.png">
      
3. Trained a Deep Neural Network with regularization for the recommender with MAE below 0.4 and MSE below 40.
      <img width="808" alt="image" src="https://user-images.githubusercontent.com/67286396/204600119-0ae46ce1-43fb-4221-9ae4-3b4507817285.png">



<p align="right">^<a href="#Contact">Back to Top</a></p>
------------------------------
### Reviews Sentiment Analyzer
[Sentiment Analyzer Code](https://github.com/annetta-zheng/sentiment_analysis)

* Results:
    * Accuracy on the test set using the original dictionary: 80.20%
    * Accuracy on the test set using the dictionary with stop words removed: 80.80%

For the perceptron algorithm: best combination of T = 25, with validation accuracy = 79.40%
![Figure_4](https://user-images.githubusercontent.com/67286396/170519190-2d1c8fb1-4c49-4dd1-a3b9-6c594bce2842.png)

For the average perceptron algorithm: best combination of T = 25, with validation accuracy = 80.00%
![Figure_5](https://user-images.githubusercontent.com/67286396/170519252-46f6b01b-04f5-49e2-ae0c-9fe2f4b33f7f.png)

For the pegasos algorithm: best combination of T = 25 \lambda = 0.01, with validation accuracy = 80.60%
![Figure_6](https://user-images.githubusercontent.com/67286396/170519444-18c2d7d5-2fbd-47d2-a296-e35c39b1bf3d.png)
![Figure_7](https://user-images.githubusercontent.com/67286396/170519453-ef692e96-dd75-4c04-a340-a28d0762a820.png)


<p align="right">^<a href="#Contact">Back to Top</a></p>

------------------------------

### Local Frog Predictor
- EY 2022 Better Working World Data Challenge, Rank 74/1222. 

[Notebook](https://github.com/annetta-zheng/Local-Frog-Predictor/blob/main/challenge.ipynb)

The output will be a species distribution model of one species of frog. Species distribution models are one of the most widely used ecological tools, a cornerstone in many countries worldwide of environmental regulation and conservation.

<img width="1101" alt="image" src="https://user-images.githubusercontent.com/67286396/171982699-807c6615-083e-420f-8fe9-0c63f1f9754b.png">


<p align="right">^<a href="#Contact">Back to Top</a></p>

------------------------------

### Blocks Game
[Blocks Puzzle Game Code](https://github.com/annetta-zheng/Blocks)

[Demo Game] (https://www.cbc.ca/kidscbc2/content/games/blocks-puzzle/index.html)

![image](https://inst.eecs.berkeley.edu/~cs61b/sp22/materials/proj/proj0/img/figure1.png)
![image](https://user-images.githubusercontent.com/67286396/157542546-95e9e541-91c9-4b81-9908-22c476265729.png)  


<p align="right">^<a href="#Contact">Back to Top</a></p>

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


<p align="right">^<a href="#Contact">Back to Top</a></p>

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


<p align="right">^<a href="#Contact">Back to Top</a></p>

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

<p align="right">^<a href="#Contact">Back to Top</a></p>

______________________________
------------------------------



