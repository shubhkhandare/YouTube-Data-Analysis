1. Project Title

# YouTube Trending Videos Data Analysis (India)

2. Project Overview

This project analyzes YouTube trending videos data using Python.
It covers data cleaning, exploratory data analysis (EDA), visualizations,
and insights about which channels, categories and video metrics perform best.

3. Dataset

Source: Kaggle – YouTube Trending Videos dataset (or synthetic generated data)

Columns used: title, channel_title, view_count, likes, comment_count, publish_time, trending_date, category, tags

Region: India (IN)

4. Tech Stack

Python

Google Colab
Libraries: pandas, numpy, matplotlib

5. How to Run
git clone https://github.com/shubhkhandare/YouTube-Data-Analysis.git
cd YouTube-Data-Analysis
pip install -r requirements.txt
googlr notebook youtube_data.ipynb

6. Analysis Performed

Data loading and cleaning

Converting date columns to datetime

Creating new time-based features (year, month, day)

Top 10 channels by number of trending videos

Average views by category

Correlation between views and likes

Monthly upload trend

7. Key Insights

Music & News categories have the highest average views

Certain channels dominate the trending list (CarryMinati, T-Series, etc. – adjust based on your results)

Correlation between likes and views is low, suggesting views don’t guarantee engagement

There is a seasonal trend in uploads across months

8. Visualizations

Bar chart: Top 10 channels by trending videos

Bar/line chart: Average views by category

Scatter plot: Views vs likes

Line chart: Monthly upload trend
