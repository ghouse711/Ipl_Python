# IPL Analytics App

A Python-based data analytics and machine learning application for analyzing Indian Premier League (IPL) matches, predicting wicket falls, and aggregating complex cricket datasets.

## Features Implemented

### Data Handling & Preprocessing
* **Data Aggregation:** Aggregated ball-by-ball cricket data into structured over-by-over summaries to extract meaningful insights using Pandas.
* **Feature Engineering:** Calculated dynamic features such as cumulative runs, wickets, previous over boundaries, dots, and run rates to feed into predictive models.

### Machine Learning Modeling
* **Wicket Prediction:** Built a Logistic Regression model to predict the likelihood of a wicket falling in an over based on match progression metrics.
* **Model Validation:** Tested the model on completely unseen data (2025 season) to ensure robust accuracy and ROC-AUC scores, with models correctly serialized.

### Comprehensive Analytics
* **Performance Metrics:** Generated in-depth analytical reports covering team scores, strike rates, economy rates, and death overs performance.
* **Automated Exports:** Seamlessly exported processed datasets and analytical results into `.csv` and Excel formats for easy visualization.

## Tech Stack
* Python 3
* Pandas (Data manipulation & aggregation)
* NumPy (Numerical operations)
* Matplotlib (Data Visualization)
* Scikit-Learn (Logistic Regression, Evaluation metrics)

## How to Run
1. Ensure you have Python installed along with `pandas`, `numpy`, `matplotlib`, and `scikit-learn`.
2. Run Jupyter notebooks located in the `Numpy` and `Pandas` directories to view the step-by-step data analysis.
3. To train and evaluate the machine learning model on 2025 IPL data, navigate to the `Pandas` directory or run from the root.
4. Execute `python Pandas/evaluate_2025.py`.
5. The processed analytics reports will be available in the `Pandas/output` folder and the final trained model will be saved in the `models` directory.
