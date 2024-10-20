# Calorie Tracker: Daily Meal and Nutrition Analysis

## Overview
The Calorie Tracker project leverages data analysis techniques to assess and visualize daily caloric intake based on meal data. Utilizing Python and Google Colab, this project integrates data from two datasets to provide actionable insights into nutritional habits.

## Data Sources
- **Calories Dataset**: Contains records of meals, their corresponding calorie counts, and dates.
- **Time of Day Dataset**: Classifies meals based on the time of day (Breakfast, Lunch, Snack, Dinner).

## Implementation Steps

### 1. Data Preparation
- **Uploading Datasets**: Both datasets were uploaded to Google Drive for easy access.
- **Mounting Drive**: Utilized Google Colab to mount the Google Drive and access the datasets.

```python
from google.colab import drive
drive.mount('/content/gdrive')
```

### 2. Data Loading
- **Reading Datasets**: Loaded the two datasets using Pandas for analysis.

```python
import pandas as pd
calories_data = pd.read_csv('/content/gdrive/My Drive/calories.csv')
time_data = pd.read_csv('/content/gdrive/My Drive/time_day.csv')
```

### 3. Data Analysis
- Conducted various analyses to answer questions about calorie intake by meal type, high-calorie meals, and overall trends.
- Implemented visualization techniques to present findings effectively.

## Project Impact
This project demonstrates the ability to analyze and interpret dietary data effectively, contributing to better nutritional choices. It serves as a personal project highlighting skills in data analysis and visualization using Google Colab.

---