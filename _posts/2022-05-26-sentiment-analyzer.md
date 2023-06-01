---
layout: post
title: Reviews Sentiment Analyzer	
tags: machine-learning python keras text-analysis data-science 
categories: [Data Science]
# permalink: "blog/:categories/:title"
---
A basic sentiment analyzer with different machine learning binary classification algorithms.

[![](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/annetta-zheng/sentiment_analysis "Click for Repo!") 
* Results:
    * Accuracy on the test set using the original dictionary: 80.20%
    * Accuracy on the test set using the dictionary with stop words removed: 80.80%

<h3>Results under different algorithms</h3>

For the perceptron algorithm: best combination of T = 25, with validation accuracy = 79.40%
![Figure_4](https://user-images.githubusercontent.com/67286396/170519190-2d1c8fb1-4c49-4dd1-a3b9-6c594bce2842.png)

For the average perceptron algorithm: best combination of T = 25, with validation accuracy = 80.00%
![Figure_5](https://user-images.githubusercontent.com/67286396/170519252-46f6b01b-04f5-49e2-ae0c-9fe2f4b33f7f.png)

For the pegasos algorithm: best combination of T = 25 \lambda = 0.01, with validation accuracy = 80.60%
![Figure_6](https://user-images.githubusercontent.com/67286396/170519444-18c2d7d5-2fbd-47d2-a296-e35c39b1bf3d.png)
![Figure_7](https://user-images.githubusercontent.com/67286396/170519453-ef692e96-dd75-4c04-a340-a28d0762a820.png)

