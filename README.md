# Data Modeling for Advertisement Click Prediction

## Overview
This project analyzes user behavior data to predict whether a user will click on an advertisement. By leveraging machine learning techniques, it uncovers patterns in the dataset and builds predictive models to classify ad click behavior.

The dataset includes demographic information, internet usage patterns, and engagement metrics, making it ideal for exploring the relationship between user characteristics and ad click-through rates.

---

## Features in the Dataset

- **Daily Time Spent on Site**: Time (in minutes) spent by the user on the website  
- **Age**: Age of the user  
- **Area Income**: Average income of the user's geographic area  
- **Daily Internet Usage**: Time (in minutes) spent by the user on the internet daily  
- **Ad Topic Line**: The headline of the advertisement shown to the user  
- **City**: The city where the user resides  
- **Gender**: Gender of the user (Male/Female)  
- **Country**: The country where the user is located  
- **Timestamp**: Date and time when the data was recorded  
- **Clicked on Ad**: Binary indicator (0 or 1) showing whether the user clicked on the advertisement  

---

## Project Goals

### Exploratory Data Analysis (EDA)
- Identify patterns and correlations between features  
- Visualize trends in advertisement click behavior  

### Data Preprocessing
- Handle missing values (if any)  
- Scale numerical features using `StandardScaler`  
- Encode categorical variables like gender and country using `LabelEncoder`  

### Dimensionality Reduction
- Use PCA and t-SNE to visualize high-dimensional data  

### Predictive Modeling
- Train machine learning models to classify whether a user clicks on an ad  
- Evaluate performance using accuracy, precision, recall, and F1-score  

---

## Technologies Used

### Data Manipulation & Analysis
- `pandas`, `numpy`  

### Data Visualization
- `matplotlib`, `seaborn`  

### Machine Learning
- `scikit-learn` for preprocessing, modeling, and dimensionality reduction  
- Algorithms used:  
  - Logistic Regression  
  - Decision Trees  
  - Random Forests  

---

## How to Run This Project

### Prerequisites
Ensure Python and the required libraries are installed. You can install dependencies via:

```bash
pip install -r requirements.txt
