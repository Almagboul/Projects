### welcome to my Data Analytics Projects


# Project 1  Udemy Courses Analysis (Data Analysis Using Python & Power BI)


### Overview
This project analyzes a dataset of Udemy courses to uncover insights about course offerings, popularity, and trends over time. The dataset includes attributes such as course title, price, number of subscribers, number of reviews, and more. The goal is to provide valuable information for business decisions and strategic planning.
### Dataset
The dataset used for this analysis is available on Kaggle: Udemy Courses .
#### source of data: https://www.kaggle.com/datasets/andrewmvd/udemy-courses/data
## Analysis and Insights
### Data Pre-processing and Exploration:
#### Checked for missing values and duplicates.
#### Explored the distribution of courses by subject and level.
#### Analyzed trends in course publication over time.
#### Examined the ratio of free vs paid courses.
#### Looked at Top 10 Courses by Number of Subscribers.
#### Also Number of Subscribers by Subject.
#### Found Number ofcourses in each subject with regard to price category
#### Also Number of courses in each subject with regard to courses levels.
### Key Findings:
#### The most popular subjects on Udemy are Web Development and Business Finance.
#### Most Popular Course: Learn HTML5 Programming From Scratch
#### A majority of courses are designed for all levels, with fewer courses targeting expert-level learners.
#### The number of courses published has increased over time, indicating a growing market for online learning.
#### Paid courses significantly outnumber free courses.
#### The most frequently used price category is between $20 and $50.
#### Total Sales: $881674940.00.
#### Average Order Value: $240107.55.

### Udemy Courses Dashboard:

![Alt text](https://github.com/Almagboul/Projects/blob/main/photos/osm%201.png)
![Alt text](https://github.com/Almagboul/Projects/blob/main/photos/osm%202.png)

### An interactive Power BI dashboard was created to enable dynamic exploration of the dataset. The dashboard includes visuals as:
### Visual 1 , Course Overview contains:

#### Trend of published courses over time
#### Distribution of free vs paid courses

#### Course distribution by subject
#### Number of courses by level

### Visual 2 , Subscriber and Pricing Overview contains:

#### Number of subscribers by subject
#### Top courses by number of subscribers

#### Number of courses in each subject with regard to price category
#### Number of courses in each subject with regard to courses levels

### Repository(Project 1/File) Contents:

##### cleaned udemy_courses.csv: Cleaned dataset used for analysis.
##### Modified _udemy_courses.csv: Modified dataset used for crating the Dashboard.
##### Project 1.ipynb & html: Jupyter notebook with data pre-processing and analysis code.
#### Project 1 PowerBI_Dashboard.pbix & pdf: Power BI files with the created dashboard.

### Conclusion
This analysis provides comprehensive insights into Udemy's course offerings and trends. The Power BI dashboard facilitates interactive exploration, making it a valuable tool for data-driven decision-making.
#### Feel free to explore the repository(Project 1/File) and the dashboard to gain deeper insights into the Udemy courses dataset.


# Project 2  Twitter Sentiment Analysis (Big Data Analytics Using Python)
 
### Introduction

 In this task I need to find and report tweets with mean or unfair words, especially those that are racist or sexist. I'll be watching all tweets, and if I find any with these bad words, I'll point them out. The main job is figuring out if a tweet is being mean about race or gender.
 This project analyzes tweets to identify those containing mean or unfair words, especially those that are racist or sexist. The primary goal is to determine if a tweet has a negative sentiment related to race or gender.
 
 ### Libraries Used
#### Data Manipulation: pandas, numpy
#### Visualization: matplotlib, seaborn, wordcloud
#### Text Processing: re, string, nltk
#### Model Building: sklearn
#### Warnings Handling: warnings
### Data Preprocessing
#### Load Dataset: Read the CSV file into a pandas DataFrame.
#### Drop Irrelevant Columns: Removed the 'id' column.
#### Remove Twitter Handles: Removed all words starting with '@' using regex.
#### Remove Special Characters: Removed non-alphabetic characters.
#### Remove Short Words: Removed words shorter than 3 characters.
#### Tokenize Tweets: Split tweets into individual words.
#### Stemming: Reduced words to their base form using the PorterStemmer.
#### Reconstruct Tweets: Combined the stemmed words back into sentences.
### Exploratory Data Analysis
#### Word Cloud Visualization
#### All Tweets: Identified commonly used words. Larger words indicate higher frequency.


#### Positive Tweets: Highlighted frequent positive words like 'love' and 'thank'.
 ### Dataset
The dataset used for this analysis is available on Kaggle: Twitter Sentiment Analysis.
 #### Source of Data: https://www.kaggle.com/datasets/arkhoshghalb/twitter-sentiment-analysis-hatred-speech?resource=download

#### Show a picture that highlights words associated with positivity:
![Alt text](https://github.com/Almagboul/Projects/blob/main/photos/Poitivity.png)

#### Negative Tweets: Highlighted frequent negative words, including racist and sexist terms like 'black' and 'women'.
#### Show a picture that highlights words associated with negativity:
![Alt text](https://github.com/Almagboul/Projects/blob/main/photos/ngetivity.png)


### Hashtag Analysis
#### Extracted hashtags from tweets to identify trends and patterns.

### Visualized the top 10 hashtags for both positive and negative sentiments.
#### Ranking and visulizing the top 10 tweets with positive sentiments:
![Alt text](https://github.com/Almagboul/Projects/blob/main/photos/posi.png)
#### Ranking and visulizing the top 10 tweets with negative sentiments:
![Alt text](https://github.com/Almagboul/Projects/blob/main/photos/neg.png)



### Feature Engineering
Feature engineering is a crucial step in preparing data for machine learning. Since machines cannot directly understand words or text, we need to convert them into vectors using TF-IDF, a technique that often provides better accuracy compared to other vectorization methods in NLP.

#### 1.Vectorization using TF-IDF: Limited the number of features to 1000 to prevent the model from considering too many features. Stop words were removed, and features were extracted from the updated tweets.
#### 2.Split Data into Training and Testing Sets:
### Model Accuracy Comparison:
#### Decision Tree: 94.65%
#### SVM: 96.24%
#### Random Forest: 92.98%
#### KNN: 94.88%
### Sentiment Prediction on New Data
#### 1.Load and Preprocess Test Data
#### 2.Vectorization and Sentiment Prediction:

### Repository(Project 2/File) Contents:

#### train & test .csv
#### Project 2.ipynb & html

### Conclusion
We analyzed commonly used words and hashtags both in general and within racist/sexist tweets. We extracted features by measuring word tokens and applying TF-IDF weighting. Then, we built several classification models to categorize future tweets, with the SVM model achieving the highest accuracy. The best model can be used to predict the sentiments of new tweets, enabling better monitoring of harmful content on social media.

#### Limitations
##### Other text preprocessing techniques might improve accuracy and evaluation scores.
##### Advanced models not tested here could potentially yield better results.
#### Strengths
#### Multiple models were tested to determine the best fit.
#### Comprehensive preprocessing ensured cleaner data for analysis.
#### Implications
##### The best model can be used to predict the sentiments of new tweets, helping to identify and address harmful content in real-time.


 #### Feel free to explore the repository(Project 2/File) to gain detailed insights.



