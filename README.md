# Customer Purchase Prediction

A machine learning model to predict customer purchase behavior (Yes/No) from social network ads using Logistic Regression.

## Problem Statement

As a data scientist, the task is to use the provided `social_network_ads.csv` dataset to build a binary classification model. The dataset includes:

-   `user_id:` The unique identifier for each user.
-   `gender:` The gender of the user.
-   `age:` The age of the user.
-   `estimated_salary:` The estimated salary of the user.
-   `purchased:` Whether the user purchased the product or not (0 for No, 1 for Yes).

The model's performance is evaluated using precision, recall, and accuracy.

**Dataset credits:** Akram (https://www.kaggle.com/datasets/akram24/social-network-ads)

## Project Structure

* `assignment_solution.ipynb`: The Jupyter Notebook containing all project code.
* `social_network_ads.csv`: The dataset used for this analysis.
* `plot.png`: A visualization of the dataset's features.
* `results.png`: A screenshot of the model's performance report.

## Libraries Used

* **Pandas:** For data loading and manipulation.
* **Matplotlib:** For data visualization.
* **Scikit-learn (sklearn):** For splitting the data, building the `LogisticRegression` model, and evaluating its performance.

## Data Visualization

The scatter plot below shows the relationship between `Age` and `Estimated Salary`, colored by the user's purchase decision. This visualization helps to show that older users with higher salaries (top right) are more likely to purchase the product (yellow dots).

![Age vs. Salary Scatter Plot](plot.png)


