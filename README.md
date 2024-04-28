

# UBS Challenge Project Documentation

## Introduction
Welcome to our project repository for the UBS Challenge. This project focuses on leveraging Instagram data to identify and capitalize on investment opportunities. This documentation provides a comprehensive overview of our analytical process, detailing our methodologies, the challenges we encountered, and the strategies we adopted to overcome these issues.

### Repository Structure
This repository is structured into several directories corresponding to the major phases of our project:
- `data`: Contains raw and processed datasets.
- `preprocessing`: Scripts for data cleaning and integration.
- `EDA`: Exploratory data analysis notebooks.
- `anomaly_detection`: Notebooks focused on identifying anomalies.

## Preprocessing
The preprocessing phase is critical as it prepares the raw data for analysis. This stage includes cleaning the data, integrating financial data from Yahoo, and creating additional features needed for anomaly detection.

### Notebooks and Scripts
- `exploration_and_cleansing.ipynb`: Walks through initial data cleaning steps, addressing missing values and deleting features not taken into account.
- `financial_data_integration.ipynb`: Integrates financial data of public companies, subsetting the original raw data.
- `feature_engineering.ipynb`: Develops new features that are crucial for effective anomaly detection.

## Exploratory Data Analysis (EDA)
After preprocessing, we conduct a thorough exploratory analysis to understand the nuances of the data better.

### Notebooks
- `general_analysis.ipynb`: Provides a broad analysis of the dataset, highlighting key statistics and distributions.
- `derived_feature_distribution_boxplots.ipynb`: Visualizes the distribution of newly created features to identify any skewness or anomalies.
- `time_series_examples.ipynb`: Examines time-series data to showcase what the data that will be used in the anomaly detection look like.

## Anomaly Detection
The anomaly detection component utilizes statistical and machine learning methods to identify unusual patterns that could signify investment opportunities.

### Notebooks
- Each notebook in this directory applies a different anomaly detection technique, allowing us to compare their effectiveness and suitability for various types of data scenarios.

------
------
# TODO:

## Modelling Approach Summary
1. **Model Selection**
   - Discussion on the choice(s) of statistical or machine learning model(s) utilized.
   - Justification for each model selected, emphasizing alignment with the project objectives.
2. **Recommendations for Model Enhancement**
   - Reflection on potential avenues for further improving the model.
   - Proposals for specific modifications or additional analyses that could refine predictions and insights.
____
____

## Challenges and Solutions
- The first challange encountered was to develope questions which we could answer given the data.
- The second challange, directly related, was to clean the data, provided the huge amount of missing values, and the its complex structure.
- The third challange was to develop an algorithm which could actually perform better than random guessing, given the little signal in the data.

Overall, the biggest issue in providing value through our approach, is directly related to the quality of the data.
The following enhancements would make our approach more effective:
- more data
- more informative features, like the comments themselves (for sentiment analysis), etc.
- no missing values 
- a clear understanding of the insights that the dataset is aiming to provide

______
_______

# TODO:

## Conclusion
Summarize the key outcomes of the project, including the effectiveness of the proposed solutions and the potential impacts on investment strategies.

## How to Use This Repository
- Download packages listed in requirements.txt
- Start with the preprocessing folder, running subsequently the three notebooks
- Take a look at the EDA folder for gaining a deeper understanding about the nuances of the data
- Take a deep dive into the Anomaly Detection folder to explore the use models and their performance

## Acknowledgments
Thanks to all contributors, data providers, and supporters who made this project possible.
