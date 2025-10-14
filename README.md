# Predicting User Spending in Digital Marketing with Machine Learning

This project focuses on applying **Machine Learning** to **Digital Marketing** to predict **how much a user will spend** on tourism packages and which package they are likely to choose. By leveraging real user behavior data from **Google Analytics**, this project enables data-driven decisions to optimize marketing strategies and improve user experience.

Developed by **Nowa Analytics**, a boutique data consultancy specializing in advanced analytics and AI solutions for businesses.



## 📌 Project Overview

The ability to **anticipate user spending** and behavior allows marketers to:

* Forecast the return of digital campaigns in advance
* Identify users experiencing friction on a website and improve their experience before they abandon
* Differentiate user segments to apply personalized marketing strategies

Even if digital marketing is not part of your day-to-day business, the techniques learned here—especially working with real user datasets—can be applied to other domains for predictive analytics and strategic insights.



## ⚙️ Project Steps

1. **Data Exploration & Analysis**

   * Understand user behavior data from Google Analytics
   * Detect patterns, outliers, and correlations
   * Visualize key insights from the dataset

2. **Data Preprocessing**

   * Transform data into JSON format
   * Encode categorical variables
   * Generate user-based features for analysis

3. **Modeling**

   * Train regression and classification models:

     * Gradient Boosting (main model)
     * Random Forest
     * Linear Regression
   * Predict both **user spending** and **package choice**

4. **Evaluation**

   * Metrics for spending prediction (regression):

     * Mean Absolute Error (MAE)
     * Mean Squared Error (MSE)
     * R² Score
   * Metrics for package prediction (classification):

     * Accuracy
     * Precision, Recall, F1-Score
     * Confusion Matrix

5. **Segmentation & Insights**

   * Cluster users based on behavior
   * Identify key characteristics of high-spending users
   * Recommend personalized marketing strategies



## 📁 Project Structure

```
📦 user-spending-ml
│
├── data/                # Raw and processed datasets (JSON)
├── notebooks/           # Jupyter Notebooks for EDA and modeling
├── src/                 # Python scripts
│   ├── preprocessing.py
│   ├── modeling.py
│   └── evaluation.py
├── results/             # Outputs, graphs, and reports
├── README.md            # This file
└── requirements.txt     # Project dependencies
```


## 📊 Technologies & Libraries

* Python 3.9+
* Pandas, NumPy
* Scikit-learn
* XGBoost
* Matplotlib, Seaborn
* Imbalanced-learn (SMOTE if needed)
* Jupyter Notebook



## ✅ Results

* Accurate prediction of user spending on tourism packages
* Identification of high-value users and behavioral patterns
* Segmentation of users to design personalized campaigns
* Insights to improve website experience and increase conversions



## 🏢 About Nowa Analytics

**Nowa Analytics** is a data consultancy focused on applying advanced analytics and AI to drive business growth. We specialize in **marketing analytics, customer behavior prediction, and data-driven strategy**.

📍 Based in São Paulo, Madrid, and London
🌐 [nowaanalytics.com](http://nowaanalytics.com) *(replace with real link if available)*



## 📬 Contact

For consulting or more information:

* 📧 [contact@nowaanalytics.com](mailto:contact@nowaanalytics.com)
* 💼 LinkedIn: [Nowa Analytics](https://linkedin.com/company/nowaanalytics)
