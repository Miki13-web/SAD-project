# SAD-project
Project created by me and a fellow student for the univeristy subject of statistical data analysis in Python. 
<div align="center">
  <h1>📊 Introverts vs. Extroverts - Data Analysis</h1>
  <p><i>Analyzing the relationship between time spent alone, social media activity, and the size of one's friend circle.</i></p>

  ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
  ![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
  ![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
  ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white)
</div>

## 📖 About the Project

This project was built in collaboration with a university classmate as part of our **Statistical Data Analysis** course. We developed and executed the entire workflow collaboratively using **Google Colab**.

The main goal of the study was to investigate whether, in the era of ubiquitous internet, online messengers, and remote work, people with introverted personalities still face difficulties in building relationships compared to extroverts. 

This repository covers the complete Data Science pipeline: from data cleaning and Exploratory Data Analysis (EDA) to training and evaluating a Machine Learning regression model.

## 🎯 Research Goal
To build a multiple linear regression model capable of predicting the **amount of time spent alone** (the dependent variable) based on:
* The size of a close friend circle (`Friends Circle Size`).
* The frequency of posting content on social media (`Post Frequency`).

## 🗂️ Dataset
We used the **"Extrovert vs. Introvert Behavior Data"** dataset (authored by Rakesh Kapilavayi, sourced from Kaggle).
* **Initial size:** `2900 records` and `8 features`.
* **After cleaning** (dropping incomplete rows and NaN values): `2477 records`.

## 🛠️ Technologies & Tools
* **Language:** Python
* **Environment:** Google Colab / Jupyter Notebook
* **Data Processing:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn

## 🔬 Analysis Workflow

1. **Data Preparation & Cleaning:** Detecting and dropping rows with missing values (NaN/nulls). Casting data types to optimize calculations.
2. **Exploratory Data Analysis (EDA):** Generating a correlation matrix for numerical variables. Creating histograms, box plots, and Q-Q plots grouped by personality types.
3. **Regression Modeling:** Splitting the data into training and testing sets. Training a multiple linear regression model.
4. **Model Evaluation:** Verifying prediction quality using standard metrics such as $R^2$, MAE, MSE, and RMSE.

## 📈 Results & Conclusions

The model achieved satisfactory and stable results, showing no signs of overfitting (the performance on the test set closely matches the training set):
* **Training set:** $R^2 = 0.6196$ | $RMSE = 2.13$
* **Test set:** $R^2 = 0.6062$ | $RMSE = 2.23$

The model explains approximately **62% of the variance** in the dependent variable.

**Key Takeaways:**
1. There is a strong, real correlation between personality type, lifestyle (including digital habits), and the size of one's friend circle.
2. Introverts spend significantly more time alone than extroverts, which confirms traditional social assumptions.
3. An increase in the number of close friends significantly decreases the predicted time spent alone.
4. Despite the growing number of online communication tools, digital solutions do not fully replace interpersonal relationships for introverts.

## 🚀 How to run the project locally?

1. Clone this repository:
   ```bash
   git clone [https://github.com/YourUsername/YourRepository.git](https://github.com/YourUsername/YourRepository.git)
