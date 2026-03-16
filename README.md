# DATA-SCIENCE


Data Analysis & Machine Learning Projects

This repository contains multiple data analysis and machine learning projects developed using Python and Jupyter Notebook. The projects demonstrate practical skills in data cleaning, exploratory data analysis, visualization, and machine learning techniques to extract meaningful insights from real-world datasets.

Tools and Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Streamlit

Project 1: Pizza Sales Data Analysis

Overview

This project analyzes a pizza store dataset containing over 48,000 transaction records. The objective was to understand sales trends, customer ordering patterns, and product performance in order to generate useful business insights that could support data-driven decision-making.

Dataset

The dataset contains order-level information including order time, pizza category, pizza size, price, and quantity purchased.

Objectives

• Understand overall revenue performance
• Identify the most popular pizza categories and sizes
• Analyze hourly and daily sales trends
• Determine top-selling pizzas
• Extract actionable business insights from the data

Process

Data Cleaning
Used Pandas to clean and preprocess the dataset by handling missing values, converting date and time columns, and verifying data consistency.

Feature Engineering
Extracted additional features such as order hour and day to analyze customer ordering behavior.

Exploratory Data Analysis (EDA)
Performed exploratory analysis to identify patterns in sales across pizza categories, sizes, and time periods.

Data Visualization
Used Matplotlib and Seaborn to create visualizations including:

• Hourly order distribution
• Revenue contribution by pizza category
• Top-selling pizzas
• Order frequency by size

Key Insights

• Large-sized pizzas were ordered most frequently
• The Classic pizza category generated the highest total revenue
• Peak order times occurred during lunch hours and evening periods
• A small group of pizzas contributed a large portion of total revenue

Business Value

These insights can help restaurant managers optimize inventory planning, pricing strategies, and staffing during peak hours.

Project 2: Customer Churn Analysis

Overview

This project analyzes a telecom customer dataset to identify patterns and factors that influence customer churn. Customer churn refers to customers leaving a service provider. Understanding churn behavior helps companies design strategies to improve customer retention.

Dataset

The dataset contains information about customer demographics, service subscriptions, contract types, tenure, monthly charges, and churn status.

Objectives

• Identify key factors contributing to customer churn
• Analyze churn patterns across different contract types
• Understand the relationship between pricing and churn behavior
• Generate insights to support retention strategies

Process

Data Cleaning and Preparation

Used Pandas to inspect the dataset, handle missing values, and convert data types for analysis.

Exploratory Data Analysis

Performed analysis to examine churn distribution across multiple variables including:

• Contract type
• Monthly charges
• Customer tenure
• Internet services
• Payment methods

Data Visualization

Created visualizations using Matplotlib and Seaborn to better understand patterns and relationships in the data.

Key Insights

• Customers with month-to-month contracts had the highest churn rate
• Higher monthly charges increased the probability of churn
• Customers with longer tenure were significantly less likely to leave
• Certain service combinations were associated with higher churn risk

Business Value

These insights can help telecom companies identify at-risk customers and design targeted retention strategies such as loyalty programs or personalized offers.

Project 3: Movie Recommendation System

Overview

This project builds a content-based movie recommendation system using movie metadata from the TMDB dataset. The system recommends similar movies based on features such as genres, cast, crew, and movie descriptions.

The recommendation engine uses Natural Language Processing techniques to transform movie metadata into numerical vectors and measure similarity between movies.

Dataset

TMDB 5000 Movies Dataset

The dataset includes information such as:

• Movie titles
• Genres
• Keywords
• Cast members
• Directors
• Movie overviews

Objectives

• Build a movie recommendation engine using content-based filtering
• Convert textual movie metadata into numerical features
• Measure similarity between movies using cosine similarity
• Provide recommendations for similar movies

Process

Data Preprocessing

Loaded movie and credits datasets and merged them based on movie title. Selected relevant columns including genres, keywords, cast, crew, and overview.

Feature Engineering

Processed metadata fields by extracting useful text features and combining them into a single feature column representing each movie.

Text Vectorization

Applied TF-IDF vectorization using Scikit-learn to convert textual movie features into numerical vectors.

Similarity Calculation

Used cosine similarity to measure the similarity between movie vectors.

Recommendation Function

Developed a recommendation function that takes a movie title as input and returns the top five most similar movies.

Model Serialization

Saved the processed dataset and similarity matrix using pickle to enable integration with a web interface.

Streamlit Application

Developed a simple interactive web application using Streamlit that allows users to select a movie and receive recommendations instantly.

Key Features

• Content-based recommendation engine
• TF-IDF text vectorization
• Cosine similarity for similarity measurement
• Interactive movie selection interface using Streamlit

Example Output

Input Movie
Avatar

Recommended Movies

• Guardians of the Galaxy
• John Carter
• Star Trek
• Aliens vs Predator
• Star Wars

Business and Industry Relevance

Recommendation systems are widely used in platforms such as Netflix, Amazon, and Spotify to personalize user experiences and increase engagement.

Skills Demonstrated

Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization
Feature Engineering
Natural Language Processing Basics
Machine Learning Concepts
Recommendation Systems
Business Insight Generation
