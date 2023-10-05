# Twitter User Gender Prediction

## Introduction

We're working on a way to get demographic info from Twitter users, even when they don't share it. Given that online marketing needs accurate info about users, like their gender, age, and location, this project can be a game-changer.

We've teamed up with Intuition Intelligence, experts in drawing business insights from social media. This partnership is a win-win: we get to use their deep knowledge, and they benefit from our research findings.

Our current focus? Twitter users in the U.S. who love the entertainment world. This helps us keep our research specific and aligns with Intuition Intelligence's main audience.

#### -- Project Status: [Completed]

## Project Objective
1) **Getting User Info:** Find ways to guess user details using their public tweets and info.
2) **Building on Existing Work:** Use and improve existing prediction models, like those on Kaggle.

### Partner
* Intuition Intelligence Inc.
* San Francisco State University -- Especially thanks Prof. Chung & Ozsen

### Achievements:
**Data Labeling Rule:** We've instituted reliable methods to label public Twitter data, understanding that the efficacy of machine learning models hinges on the quality of labeling.
**Baseline Model for Gender Prediction:** Detailed breakdown of our machine learning processes from data preprocessing to prediction is provided. Notably, our model is structured with two layers, encompassing eight weak learners and a master classifier for predictions. Metrics such as accuracy score, recall, precision, F1 score, and AUC are employed to validate and fine-tune our model.

### Technologies and Methods Used
* Data Collection & Processing: Twitter API, Inferential Statistics
* Text Analysis: Text Mining, Natural Language Processing (NLP)
* Modeling: Machine Learning, Stacking Model
* Tools: Python, Colab, Jupyter Notebook, Pandas, BERT, Scikit-learn, LucidChart, Tableau

## Project Description
### Data source:
Self-collected data from Twitter API:  
Raw data size: 400k x 100 attributes  
Actual training size: 2,029 x 12 attributes (After labeled and feature selection)

### Assumption:
1) Twitter users’ writing style is different by gender groups. This fundamental assumption allows 
   us to utilize text features for our prediction modeling.  
2) All Twitter users have an equal willingness to disclose demographic data in their Twitter account profile. 
   This assumption ignores the sample bias for our manually labeling process.

## Repository Contents: 
  1. [Twitter API Streamer ](Notebooks/Twitter_app_streamer.ipynb) - Data collection
  2. [Gender Prediction Model](Notebooks/gender.ipynb)
  3. [Presentation Slides](https://github.com/Liam-LT/Twitter_User_Gender_Age_Detection/blob/master/Slides/TwitterProject.pdf)

