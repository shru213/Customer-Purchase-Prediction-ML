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

* `assignment_solution.ipynb`: The Jupyter Notebook containing all steps from data loading and exploration to model training and evaluation.
* `social_network_ads.csv`: The dataset used for this analysis.

## Libraries Used

* **Pandas:** For data loading and manipulation.
* **Matplotlib:** For data visualization.
* **Scikit-learn (sklearn):** For splitting the data, building the `LogisticRegression` model, and evaluating its performance with a `classification_report`.



## How to Run This Project

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/YOUR_USERNAME/Customer-Purchase-Prediction.git](https://github.com/YOUR_USERNAME/Customer-Purchase-Prediction.git)
    cd Customer-Purchase-Prediction
    ```
    *(Remember to replace `YOUR_USERNAME` with your actual GitHub username!)*

2.  **Install the required libraries:**
    ```sh
    pip install -r requirements.txt
    ```

3.  **Run the Jupyter Notebook:**
    Launch Jupyter Notebook or Jupyter Lab and open the `assignment_solution.ipynb` file.
    ```sh
    jupyter notebook assignment_solution.ipynb
    ```

## Model Results

The logistic regression model was trained on 70% of the data and evaluated on the 30% test set.

**Classification Report:**

The report shows how well the model predicted purchases on new data it hadn't seen before. The accuracy is 89%.

```
              precision    recall  f1-score   support

           0       0.88      0.96      0.92        73
           1       0.91      0.79      0.85        47

    accuracy                           0.89       120
   macro avg       0.90      0.87      0.88       120
weighted avg       0.89      0.89      0.89       120
```
