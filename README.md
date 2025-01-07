# Customer Segmentation Project
---
## Overview
This project focuses on segmenting customers into distinct groups based on their spending behavior and income levels. By applying **K-Means Clustering**, this analysis helps businesses understand their customer base better and optimize marketing strategies.
---
## Objectives
- Perform clustering on customer data to identify meaningful customer groups.
- Analyze patterns and behaviors within each segment.
- Provide actionable insights for business strategies.
---
## Dataset
- **Source**: [Mall Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) from Kaggle.
- **Key Features**:
  - `CustomerID`: Unique identification for each customer.
  - `Gender`: Gender of the customers.
  - `Age`: Age of the customers.
  - `Annual Income (k$)`: Customer annual income in thousands.
  - `Spending Score (1–100)`: Score assigned by the business based on customer behavior.
---
## Requirements
To run this project, you need the following:
- python.3x
- Required python libraries
  - pandas
  - matplotlib
  - seaborn
  - scikit-learn
---
### Methodology
1. **Exploratory Data Analysis (EDA)**:
   - Visualized age, income and spending distributions.
   - Analyzed patterns and trends in customer data.
2. **Correlation Analysis**:
   - Examined relationships between features to ensure they contribute meaningfully to clustering.
3. **K-Means Clustering**:
   - Used the Elbow Method to determine the optimal number of clusters.
   - Visualized the clusters to interpret group characteristics.
---
## Findings
- For a detailed explanation of the findings, please refer to the [Jupyter Notebook](https://github.com/Thanmai-40/CodeClauseInternship_CustomerSegmentation/blob/master/Customer_Segmentation.ipynb).
---
## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Thanmai-40/CodeClauseInternship_CustomerSegmentation.git
   cd CodeClauseInternship_CustomerSegmentation
