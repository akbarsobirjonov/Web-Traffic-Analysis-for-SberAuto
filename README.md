
📊 Final Project: Web Traffic Analysis for SberAutoSubscription

Course: Introduction to Data 

ScienceAuthor: Akbar

Language: Python + Jupyter Notebook

Project type: Exploratory Data Analysis + Hypothesis Testing (Data Analyst specialization)


🏢 About the Project

This project is based on real analytical tasks from SberAutoSubscription, a Russian service offering long-term car rentals. The goal was to explore web traffic data collected via Google Analytics, evaluate user behavior, and provide data-driven answers to product questions.
The dataset includes detailed information on user sessions and interactions with the website — device types, traffic sources, user actions, and more.

✅ Objectives
1. Data Preparation

-Read and explore both datasets (ga_sessions.pkl and ga_hits.pkl)

-Assess data completeness and cleanliness

-Normalize and preprocess for further analysis

2. Exploratory Data Analysis (EDA)

-Remove duplicates and irrelevant columns

-Handle missing values and incorrect types

-Visualize key attributes (e.g., device category, city, traffic source)

-Analyze CR (conversion rate) per session

3. Hypothesis Testing

-Using statistical tests (like z-test or chi-squared test), the following hypotheses were tested:

-There is no difference in conversion rate (CR) between organic and paid traffic

-There is no difference in CR between mobile and desktop devices

-There is no difference in CR between users from major cities (Moscow, SPb) and other regions

4. Business Questions Answered

-Which traffic sources bring the most target traffic (volume + CR)?

-Which car models are the most popular and have the best CR?

-Should we invest more in social media advertising?


📈 Tools & Libraries

-pandas, numpy

-matplotlib, seaborn

-scipy.stats for hypothesis testing

-Jupyter Notebook for interactive analysis
