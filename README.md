
**Analysis of Online Reviews for Customer Experience Insights**

**Overview**
This project aims to extract actionable insights from user-generated reviews on a major online platform to predict customer satisfaction and product quality through ratings. By analyzing reviews, ratings, and accompanying metadata, we aim to reveal patterns and sentiments that significantly impact customer experience.

**Objectives**
Develop a predictive model that can accurately forecast review ratings based on textual feedback.
Enable businesses to enhance their services and assist consumers in informed decision-making.
Methodology
**Data Exploration**
Early data exploration underscored the dataset's potential for deep sentiment analysis and predictive modeling. Preliminary interactions with the dataset demonstrated its appropriateness for detailed sentiment analysis and accurate rating predictions.

**Sentiment Analysis**
Sentiment Categorization: Used VADER for initial sentiment categorization.
Text Processing: Applied advanced text processing techniques (tokenization, lemmatization) via NLTK to prepare data for predictive modeling.
Predictive Modeling
**Model:** Developed a BiLSTM deep learning model using Keras.
**Objective:** Predict review ratings by understanding the intricacies of textual sentiment.
Challenge Addressed: Correlating the nuanced sentiment of text data with numerical rating outcomes.
**Preliminary Results**
Initial exploration identified the dataset as a rich source for analysis.
Comprehensive metadata supports the project's predictive objectives.
Data compatibility with our analysis methods confirmed.
Promising potential for developing a reliable predictive model for review ratings.
Example Data
No	Review	Rating	Sentiment Score	Sentiment
1	spacious rooms with excellent service	5	0.9632	Positive
2	average stay, unimpressive breakfast	3	0.6548	Neutral
3	poor cleanliness, would not recommend	1	0.2345	Negative
4	amazing amenities, friendly staff	5	0.9876	Positive
5	moderately priced, great location	4	0.7599	Positive
**Visualization**
A bar chart visualizing the distribution of sentiments among the reviews illustrates the predominance of positive sentiments within the dataset, providing a clear, immediate visual understanding of overall sentiment trends.

**References**
Dataset on Zenodo
Hotel Review Analysis using Deep Learning
Predicting Review Ratings using Machine Learning
Sentiment Analysis with Hotel Reviews on Kaggle
**Contributors**
Aishwarya Kumar Arvind
Gargi Girish Umrajkar
Raghul S
Vandit Gupta
Vinayaka Hosahalli Kotrappa
