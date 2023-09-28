---
layout: post
title: Sentiment Analysis and Music Recommendations Systems	(Deep Learning)
tags: machine-learning python deep-learning keras text-analysis natural-language-processing data-science 
categories: [Data Science, Python]
# permalink: "blog/:categories/:title"
---
A review-based recommendation system with natural language processing (NLP) and Collaborative Filtering on 1.5M review data and 75k music meta data, utilizing Python via keras framework on an AWS EC2 instance.

[![](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/annetta-zheng/music-recommender "Click for Repo!")

### Key Steps:
<table class = "mur-tbl">
  <tr><th>Step 1. Convolutional Neural Network</th></tr>
  <tr>
    <td colspan="2"> 
      with NLTK for Sentiment Analysis<br>Results: 91.4% Test Accuracy
    </td>
  </tr>
  <tr>
    <td>Most significant token in review</td>
    <td>Most significant token in summary</td>
  </tr>
  <tr>
    <td>
      <img style="align:center" alt="image" src="https://user-images.githubusercontent.com/67286396/204599154-f5964ddd-9138-49c9-8e1b-fd5b70d0f30f.png">
    </td>
    <td>
      <img style="align:center" alt="image" src="https://user-images.githubusercontent.com/67286396/204599389-b72f1da1-b877-4eab-88c0-74d2500b6908.png">
    </td>
  </tr>
  <tr>
    <td colspan="2">
      <img style="align:center" alt="image" src="https://user-images.githubusercontent.com/67286396/204599514-0c6ab305-e115-403f-bf68-8135e06a339b.png">
    </td>
  </tr>
</table>

<table class = "mur-tbl">
  <tr><th>Step 2. Stacked Autoencoder</th></tr>
  <tr>
    <td> 
      with SGD for tokens' Dimension Reduction
    </td>
    </tr>
  <tr>
    <td>
      <img style="align:center" height=300px alt="image" src="https://user-images.githubusercontent.com/67286396/204599574-3ae71217-c4e7-40e4-a336-ee15429344c3.png">
    </td> 
  </tr>
</table>


<table class = "mur-tbl">
  <tr><th>Step 3. Deep Neural Network</th></tr>
  <tr>
    <td> 
      with Regularization for the recommender<br>
      Results: MAE below 0.4 & MSE below 40
    </td>
  </tr>
  <tr>
    <td>
      <img style="align:center" alt="image" src="https://user-images.githubusercontent.com/67286396/204600119-0ae46ce1-43fb-4221-9ae4-3b4507817285.png">
    </td>  
  </tr>
</table>  
  

