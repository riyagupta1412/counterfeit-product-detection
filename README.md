# Counterfeit Product Detection using Predictive Analytics & Machine Learning

## Overview
This project focuses on developing a Predictive Analytics framework to identify counterfeit products in e-commerce marketplaces using Machine Learning and Classification Models.

Counterfeit products pose significant financial, operational, and reputational risks to online marketplaces, brands, and consumers. The objective of this project was to build a data-driven counterfeit detection system capable of proactively identifying high-risk product listings and suspicious seller behavior.

The project was conducted as part of an MBA coursework assignment in Predictive Analytics and Business Analytics.

---

## Business Problem
Counterfeit products on e-commerce platforms:
- Reduce consumer trust
- Damage brand reputation
- Create financial losses for legitimate businesses
- Increase operational burden through manual verification processes

Traditional manual detection methods are difficult to scale due to the increasing sophistication of counterfeit sellers. This project aimed to leverage Machine Learning techniques to automate counterfeit detection and improve marketplace integrity.

---

## Dataset Description

### Dataset Characteristics
- 10,000+ observations
- 26 variables
- Binary target variable: `is_counterfeit`

### Key Features Included
#### Seller Information
- Seller rating
- Seller reviews
- Seller country
- Domain age
- Contact information completeness
- Return policy clarity

#### Product & Listing Features
- Product category
- Brand
- Product price
- Shipping information
- Description length
- Product images
- Spelling errors

#### Behavioral Indicators
- Unusual payment patterns
- IP location mismatch
- Bulk order availability
- Certification badges

---

## Data Preprocessing
- Removed duplicate records
- Standardized categorical variables
- Handled missing values using mean/mode imputation
- Prepared data for classification modeling and validation

---

## Machine Learning Models Evaluated

### 1. Decision Tree
Used for:
- Model interpretability
- Rule-based classification
- Business decision support

### 2. K-Nearest Neighbors (KNN)
Used for:
- Baseline performance benchmarking
- Similarity-based classification analysis

### 3. Bootstrap Forest (Random Forest Ensemble)
Used for:
- Improved prediction accuracy
- Reduced overfitting risk
- Better generalization performance

---

## Model Evaluation Metrics
The models were evaluated using:
- Accuracy
- ROC-AUC
- Recall
- Sensitivity
- Specificity
- Misclassification Rate
- Confusion Matrix Analysis

---

## Key Findings

### Important Counterfeit Risk Drivers
- Incomplete seller contact information
- Weak or missing return policies
- Unusual payment patterns
- Bulk order behavior
- IP location mismatches

### Model Insights
- Decision Tree and KNN achieved near-perfect accuracy but showed signs of overfitting.
- Bootstrap Forest demonstrated stronger real-world reliability with balanced performance and better generalization capability.

### Final Recommendation
Bootstrap Forest was identified as the most reliable production-ready model for counterfeit detection due to its:
- Robust predictive performance
- Lower overfitting risk
- Better scalability for real-world deployment

---

## Business Recommendations
- Implement automated seller risk scoring systems
- Flag suspicious listings for manual review
- Enforce stricter seller onboarding verification
- Monitor abnormal payment and shipping behaviors
- Continuously retrain models with updated marketplace data

---

## Technical Skills Applied
- Predictive Analytics
- Machine Learning
- Classification Modeling
- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)
- Data Preprocessing
- Data Cleaning
- Statistical Analysis
- Model Evaluation
- ROC-AUC Analysis
- Confusion Matrix Analysis
- Fraud Detection
- Risk Scoring
- Business Analytics
- Data Visualization
- JMP

---

## Tools & Technologies Used
- JMP
- Microsoft Excel
- Machine Learning Classification Techniques
- Statistical Modeling Methods

---

## Repository Structure

```bash
├── Dataset/
│   └── counterfeit_products.csv
│
├── Models/
│   ├── Decision_Tree_Model.jrp
│   ├── KNN_Model.jrp
│   ├── Bootstrap_Forest_Model.jrp
│   └── Naive_Bayes_Model.jrp
│
├── Report/
│   └── Counterfeit_Product_Detection_Report.pdf
│
└── README.md
