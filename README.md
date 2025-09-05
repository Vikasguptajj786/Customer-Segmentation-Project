Mall Customer Segmentation Analysis
This project performs an in-depth exploratory data analysis (EDA) and customer segmentation on the Mall Customers dataset. The goal is to understand customer behavior and identify distinct groups based on their shopping habits, which can be used to develop targeted marketing strategies.

The dataset for this project is publicly available on Kaggle and can be downloaded from the following link: "https://www.kaggle.com/datasets/vikasjigupta786/customer-analytics-practice-dataset"

📋 Table of Contents
Project Overview

Dataset

Tools and Libraries

Analysis Workflow

Key Visualizations

How to Run This Project

📝 Project Overview
The main objective of this analysis is to identify different customer personas within a mall. By understanding the relationships between demographic information (age, gender) and spending patterns (annual income, spending score), we can provide valuable insights for the mall's marketing and management teams.

📊 Dataset
The dataset used in this project can be found on Kaggle.

Link: Customer Analytics Practice Dataset

It contains the following columns:

CustomerID: Unique ID for each customer.

Gender: The gender of the customer.

Age: The age of the customer.

Annual Income (k$): The annual income of the customer in thousands of dollars.

Spending Score (1-100): A score assigned by the mall based on customer behavior and spending nature (1 is low, 100 is high).

Estimated Savings (k$): The estimated savings of the customer in thousands of dollars.

🛠️ Tools and Libraries
This project is implemented in a Jupyter Notebook and utilizes the following Python libraries:

Data Manipulation: pandas, numpy

Data Visualization: matplotlib, seaborn

Automated EDA: dabl

Data Preprocessing: scikit-learn

⚙️ Analysis Workflow
Data Loading and Cleaning: The dataset was loaded, and an initial check was performed to ensure there were no missing values.

Descriptive Statistics: Summary statistics were generated for both numerical and categorical data to get a high-level understanding.

Exploratory Data Analysis (EDA):

Visualized the distribution of key features such as Age, Annual Income, and Spending Score.

Analyzed the gender distribution of customers.

Explored the relationships between different variables using scatter plots, box plots, and pairplots to uncover patterns.

✨ Key Visualizations
Below are some of the key charts from the analysis that highlight customer trends.

(Pro-Tip: Take screenshots of your best plots from the notebook and add them here by dragging and dropping them into this README file on GitHub.)

1. Distribution of Annual Income and Spending Score
<br>
[Your screenshot of the distribution plots would go here]
<br>

2. Age vs. Spending Score
<br>
[Your screenshot of the Age vs. Spending Score scatter plot would go here]
<br>

3. Gender Distribution
<br>
[Your screenshot of the gender pie chart would go here]
<br>

🚀 How to Run This Project
To replicate this analysis on your local machine, follow these steps:

Clone the repository:

git clone https://github.com/Vikasguptajj786/Customer-Segmentation-Project.git
cd Customer-Segmentation-Project

Install the required libraries:

pip install pandas matplotlib seaborn dabl scikit-learn jupyterlab

Launch Jupyter Lab:

jupyter lab

Run the Notebook: Open the Customer Segmentation for Targeted Retail Marketing.ipynb file and run the cells sequentially.
