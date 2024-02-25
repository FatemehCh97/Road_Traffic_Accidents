# Road Accident Analysis

## Overview
This project aims to analyze road traffic accidents using a comprehensive dataset collected from the UK government's official statistics. The dataset contains detailed information on accident status, vehicle and casualty references, demographics, and severity of casualties. By leveraging data-driven approaches, the project seeks to understand the factors contributing to accident occurrence and severity, as well as to provide insights for reducing accidents and enhancing road safety measures.


## Installation

1. Clone the Repository
    ```
    git clone <repository_url>
    cd road_accident_analysis
    ```


2. Install Requirements
    ```
    pip install -r requirements.txt
    ```

## Methodology
### Data Collection
The dataset used in this project was sourced from the UK government's official statistics on road traffic accidents. It provides comprehensive insights into road accidents reported over multiple years, including various attributes related to accident status, vehicle and casualty references, demographics, and severity of casualties.

### Data Preprocessing
Preprocessing steps were conducted to improve data quality and prepare it for analysis and modeling. This included handling missing values, removing irrelevant and highly correlated columns, and standardizing numerical variables using standard scaling.

### Exploratory Data Analysis (EDA)
Descriptive statistics, visualizations, and correlation analysis were performed to gain insights into the dataset, such as casualty severity counts, casualty class distributions, gender distribution, age of casualty distributions, distribution of casualty types, pedestrian location and movement distributions, and relationships of factors with casualty severity.

### Model Development
A logistic regression model was utilized to predict casualty severity based on various factors. The model was evaluated using mean absolute error (MAE), mean squared error (MSE), and accuracy metrics.

### Feature Importance Analysis
The feature importance of the logistic regression model was examined to identify significant predictors of casualty severity. This analysis helped in understanding which factors had the most influence on predicting casualty severity levels.

## Results and Discussion
The results highlighted key findings from the analysis, including the relationship between different factors and casualty severity. For example, factors such as casualty class, age of casualty, and area type were found to be correlated with casualty severity. Recommendations for reducing accidents and enhancing road safety measures were also discussed based on the insights gained from the analysis.

## Conclusion
In conclusion, this project provided valuable insights into road accident analysis and offered recommendations for reducing accidents and enhancing road safety. By leveraging data-driven approaches and implementing targeted interventions, stakeholders can work towards the goal of creating safer roadways for all users.

