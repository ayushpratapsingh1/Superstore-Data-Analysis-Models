# Superstore Data Analysis Project

## Project Overview

This project analyzes the Superstore dataset using R programming to explore the impact of factors such as gender, time of day, date, and month on sales performance. The analysis includes applying machine learning models (SVM, Naive Bayes, Multiple Regression, and K-means Clustering) to provide valuable insights into customer behavior, sales trends, and model performance metrics. The objective is to evaluate the performance of these models using accuracy, precision, and confusion matrices, helping businesses make data-driven decisions for optimization.

## Key Features
- **Data Preprocessing**: Cleans and transforms raw sales data for analysis.
- **Machine Learning Models**: Implements SVM, Naive Bayes, Multiple Regression, and K-means Clustering to predict and classify data.
- **Model Evaluation**: Analyzes the models using confusion matrices, accuracy, and precision metrics.
- **Insights Extraction**: Investigates the impact of gender, time of day, date, and month on sales performance.
- **Visualization**: Utilizes data visualization to present findings and trends.

## Tech Stack
- **R**: For data manipulation, machine learning, and analysis.
- **ggplot2**: For visualizations.
- **caret**: For training and evaluating machine learning models.
- **dplyr**: For data preprocessing.
- **e1071**: For SVM model implementation.

## Setup Instructions

To run the project locally, follow these steps:

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/ayushpratapsingh1/Superstore-Data-Analysis.git
    cd Superstore-Data-Analysis
    ```

2. **Install Dependencies**: Ensure you have R installed and required libraries using the following commands:

    ```r
    install.packages(c("ggplot2", "caret", "dplyr", "e1071"))
    ```

3. **Run the Project**:

    Open the `Superstore_Data_Analysis.R` file in RStudio or another R environment and run the script.

    ```r
    source('Superstore_Data_Analysis.R')
    ```

    The analysis will run, and the outputs will be displayed in the console.

## Models Used
- **Support Vector Machine (SVM)**: A classification model to predict outcomes based on hyperplanes.
- **Naive Bayes**: A probabilistic classifier based on Bayes' theorem.
- **Multiple Regression**: For predicting numeric sales data based on various factors.
- **K-means Clustering**: A clustering algorithm used to identify patterns in customer segments.

## Model Evaluation Metrics
- **Accuracy**: Measures the proportion of correctly predicted instances.
- **Precision**: Measures the accuracy of the positive predictions made by the model.
- **Confusion Matrix**: Displays the true positives, false positives, true negatives, and false negatives.

## Insights
- Gender, time of day, date, and month significantly affect sales.
- The models provide insights into which features influence customer buying behavior.
- K-means clustering helps segment customers for targeted marketing.

## How to Contribute
Contributions are welcome! Here's how you can contribute:
1. **Fork the repository**.
2. **Create a branch** for your feature or bug fix:
    ```bash
    git checkout -b feature-name
    ```
3. **Commit your changes**:
    ```bash
    git commit -m 'Add feature or fix bug'
    ```
4. **Push to the branch**:
    ```bash
    git push origin feature-name
    ```
5. **Submit a pull request**.

