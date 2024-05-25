# Olympic Data Analysis Project

## Overview

This project analyzes Olympic Games data to extract meaningful insights, focusing on the distribution of medals among athletes. The analysis includes creating visualizations to help understand the data better. This README provides an overview of the project, the data used, the steps of the analysis, and instructions to reproduce the results.

## Data

The dataset used in this project is sourced from [Kaggle](#https://Kaggle) and it contains information about athletes, the events they participated in, and the medals they won in the Olympic Games. The data includes the following columns:
- `Name`: The name of the athlete.
- `Sex`: The gender of the athlete.
- `Age`: The age of the athlete.
- `Height`: The height of the athlete.
- `Weight`: The weight of the athlete.
- `Team`: The team or country the athlete represents.
- `NOC`: National Olympic Committee three-letter code.
- `Games`: Year and season of the Olympics.
- `Year`: Year of the Olympics.
- `Season`: Season of the Olympics (Summer or Winter).
- `City`: Host city of the Olympics.
- `Sport`: Sport in which the athlete competed.
- `Event`: Specific event in which the athlete competed.
- `Medal`: Medal won by the athlete (Gold, Silver, Bronze, or NA).

## Project Steps

### 1. Data Loading and Preprocessing

The first step involves loading the dataset and performing preprocessing tasks such as handling missing values, data cleaning, and ensuring data types are appropriate for analysis.

### 2. Exploratory Data Analysis (EDA)

EDA is conducted to understand the basic properties of the data, including:
- Distribution of athletes by gender.
- Number of participants over the years.
- Top countries by the number of medals won.
- Trends in different sports.

### 3. Medals Analysis

This step focuses on analyzing the medal counts:
- Counting the number of medals won by each athlete.
- Identifying top athletes based on their medal counts.

### 4. Visualization

- Visualizations like a bar plot is created to display the top 10 athletes by the number of medals won.
- A pie plot to display the top popular sports in Olympics.
- A scatter plot to display the height vs wights of Olympic Medallist.
- A bar plot to display the top athletes based on their medal counts.
- A bar plot to display the top participating countries in Summer and Winter Seasons.
