## Welcome to My Data Analytics Projects
# Project 1  BIG DATA Analytics(NLP) Using Python
## (Title:Twitter Sentiment Analysis)
 #### Source of Data: https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech?resource=download
### Introduction

 In this task I need to find and report tweets with mean or unfair words, especially those that are racist or sexist. I'll be watching all tweets, and if I find any with these bad words, I'll point them out. The main job is figuring out if a tweet is being mean about race or gender.


### Show a picture that highlights words associated with positivity.
![Alt text](https://github.com/Almagboul/Project/blob/main/Poitivity.png)

### Ranking and visulizing the top 10 tweets with positive sentiments.
![Alt text](https://github.com/Almagboul/Project/blob/main/posi.png)

  
### Repository Contents
#### Project 1 File contains
##### train & test .csv
##### Project 1.ipynb & html
### Conclusion
 We analyzed commonly used words and hashtags both in general and within racist/sexist tweets. We extracted features by measuring word tokens and applying Tfidf weighting. Then, I built two classification models: Decision Trees model and a support vector classifier to categorize future tweets.Due to the limitations of machines in processing text-based data, it is imperative to convert the data into a numerical format for effective handling.By simplifying and filtering the text, we generate cleaner data for processing, ultimately leading to improved outcomes.To assess the results, we can employ various machine learning techniques for comparison.
#### Limitation
1. Although I looked at some text preprocesssing techniques, other texts might produce better accuracies and evaluation scores of the best models (or other models).
2. Other advanced models that were not tested here could probably be a better fit and produce better evaluation scores.
#### Strength
 Different models were tested on the data to find out which one is the best.
#### Implication
 The best model can be used to predict the sentiments of new tweets that are generated.




# Project 2 Data Analysis Using Python & Power BI
## (Title: Udemy Courses Analysis)

### Overview
This project analyzes a dataset of Udemy courses to uncover insights about course offerings, popularity, and trends over time. The dataset includes attributes such as course title, price, number of subscribers, number of reviews, and more. The goal is to provide valuable information for business decisions and strategic planning.
### Dataset
The dataset used for this analysis is available on Kaggle: Udemy Courses .
#### source of data: https://www.kaggle.com/datasets/andrewmvd/udemy-courses/data
### Analysis and Insights
### Data Pre-processing and Exploration:
Checked for missing values and duplicates.
Explored the distribution of courses by subject and level.
Analyzed trends in course publication over time.
Examined the ratio of free vs paid courses.
Looked at Top 10 Courses by Number of Subscribers.
Also Number of Subscribers by Subject.
Found Number ofcourses in each subject with regard to price category
Also Number of courses in each subject with regard to courses levels.
Key Findings:
The most popular subjects on Udemy are Web Development and Business Finance.
A majority of courses are designed for all levels, with fewer courses targeting expert-level learners.
The number of courses published has increased over time, indicating a growing market for online learning.
Paid courses significantly outnumber free courses.
The most frequently used price category is between $20 and $50.
### Udemy Courses Dashboard

![Alt text](https://github.com/Almagboul/Projects/blob/main/photo/osm%201.png)
![Alt text](https://github.com/Almagboul/Projects/blob/main/photo/osm%202.png)

### An interactive Power BI dashboard was created to enable dynamic exploration of the dataset. The dashboard includes visuals such as:
Course distribution by subject
Number of courses by level
Trend of published courses over time
Distribution of free vs paid courses
Top courses by number of subscribers
Number of subscribers by subject
Number of courses in each subject with regard to price category
Number of courses in each subject with regard to courses levels
### Repository Contents
#### Project 2 File contains
##### cleaned udemy_courses.csv: Cleaned dataset used for analysis.
##### Modified _udemy_courses.csv: Modified dataset used for crating the Dashboard.
##### Project 2.ipynb & html: Jupyter notebook with data pre-processing and analysis code.
#### Project 2 PowerBI_Dashboard.pbix & pdf: Power BI files with the created dashboard.

### Conclusion
This analysis provides comprehensive insights into Udemy's course offerings and trends. The Power BI dashboard facilitates interactive exploration, making it a valuable tool for data-driven decision-making.
Feel free to explore the repository and the dashboard to gain deeper insights into the Udemy courses dataset.


