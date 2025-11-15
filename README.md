## Abstract

This project constructs a streaming content dashboard for exploring and visualizing data on popular shows from Netflix, Hulu, Disney+, and Amazon Prime. It leverages K-Means clustering to develop a recommendation system that suggests similar movies based on a user's watch history.

## Keywords

Netflix, Hulu, Disney Plus, Amazon Prime, Recommendation System, Text Clustering, Data Visualization & Analytics, OTT Content, K-Means Algorithm.

## Introduction

Recommender systems have become crucial for navigating the vast information landscapes of today's streaming platforms. These systems learn user preferences and suggest personalized content. In this project, we focus on visualizing the content libraries of top OTT platforms like Netflix, Disney Plus, Hulu, and Amazon Prime. Our goals include:

Unveiling fascinating correlations and patterns within the dataset.
Constructing an interactive dashboard that aids exploration and understanding of streaming content.
Implementing a recommendation system powered by K-Means clustering to suggest similar content based on user watch history.

## Data Description

The project utilizes four datasets, each containing details about movies and TV shows available on their respective platforms: Netflix, Hulu, Disney Plus, and Amazon Prime. These datasets include attributes like:

Cast
Director
Duration
Release Year
Ratings
Title
Description
Country
Listed In
Date Added
Each dataset comprises roughly 22,000 observations. The combined dataset, obtained from Kaggle's Open-Source Dataset Library, incorporates these attributes along with a new column indicating the OTT platform.

## Methodology and Data Flow

This project follows a meticulously designed workflow:

## 1. Data Cleaning and Exploration:

Importing datasets using libraries like pandas.
Performing data cleaning tasks to ensure consistency and handle missing values.
Analyzing data characteristics to identify suitable visualization strategies.

## 2. Exploratory Data Analysis (EDA) and Visualization (Python):

Employing libraries like matplotlib or Seaborn to generate visualizations.
Analyzing relationships and dependencies between data attributes.
Creating visualizations that effectively convey insights.

## 3. Interactive Dashboard Creation using Tableau:

Leveraging Tableau's functionalities to construct visually appealing and interactive dashboards.
Facilitating easy exploration of streaming content data through interactive elements.

### 4. K-Means Clustering and Recommendation System:

Applying the K-Means clustering algorithm to group similar shows and movies.
Assigning cluster labels to data points.
Building a recommendation engine that:
Accepts a movie/show title as input.
Identifies the cluster to which it belongs.
Recommends similar shows/movies within the same cluster using text similarity techniques.


## Contribution

This project offers valuable insights into streaming content data analysis and visualization. It demonstrates the application of K-Means clustering for building a recommendation system. Feel free to explore the code and dashboards!


<img width="1919" height="920" alt="image" src="https://github.com/user-attachments/assets/13fb07e7-bf46-4269-ab82-fdceb0f54697" />
<img width="632" height="412" alt="image" src="https://github.com/user-attachments/assets/52f11567-ca31-4c98-be5a-f7000cbb1cfd" />


