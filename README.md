# Cancelation-Hotel-Booking-analysis-and-predictive-model
Project data science, by do analysis using transaction and history hotel booking data and build predictive model to identify high risk customer to cancel the hotel booking
# Hotel Booking Cancellation Analysis & Predictive Model
*by Tarfa Gaida*

## Overview

This project leverages transaction and historical hotel booking data to analyze customer behaviors and develop a predictive model to identify high-risk customers likely to cancel their hotel bookings. The insights from this analysis aim to support better business decisions and reduce revenue loss from cancellations.

## Business Impact

- **Risk Identification:** Accurately flag potential booking cancellations, empowering proactive customer engagement.
- **Data-Driven Decisions:** Provides actionable insights to improve booking policies, customer retention, and revenue management.
- **Visualization:** Key findings are illustrated through charts for intuitive understanding and presentation to stakeholders.

## Technology Stack

- **Primary language:** Python
- **Data Analysis & Modeling:** pandas, numpy, scikit-learn
- **Visualization:** matplotlib, seaborn

## Project Structure

- `notebooks/` — Main Jupyter notebooks for EDA, modeling, and results
- `data/` — Input datasets (https://drive.google.com/file/d/1afGNqlSQJsToCk1dIh6b-JULY-beYFnb/view?usp=sharing)
- `output/` — Generated charts and model results

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/TarfaGaida/Cancelation-Hotel-Booking-analysis-and-predictive-model.git
   ```

2. **Install dependencies:**  
   Open in [Google Colab](https://colab.research.google.com/) or run locally in Jupyter Notebook.  
   Install required libraries if running locally:
   ```bash
   !pip install dalex
   !pip install scikit-plot
    ```
    ```bash
   # load pandas untuk data wrangling
   import pandas as pd
   # load numpy untuk manipulasi vektor
   import numpy as np
   # load matplotlib untuk visualisasi data
   import matplotlib.pyplot as plt
   # load seaborn untuk visualisasi data
   import seaborn as sns
    ```

   ```bash
   # load metrics object dari sklearn
   from sklearn import metrics
   # load train-test data splitter
   from sklearn.model_selection import train_test_split
   # load Decision Tree classifier model
   from sklearn.tree import DecisionTreeClassifier
   # load Random Forest classifier model
   from sklearn.ensemble import RandomForestClassifier
   #load logisic regression classifier model
   from sklearn.linear_model import LogisticRegression
   # load xgboost classifier model
   from xgboost import XGBClassifier
   ```

3. **Run the analysis:**  
   Open the main notebook and follow the steps for EDA, modeling, and results visualization.



## Contact

For questions or collaboration:
- GitHub: [TarfaGaida](https://github.com/TarfaGaida)

---

*This project is for educational and demonstration purposes. Data is anonymized and used in compliance with privacy guidelines.*
