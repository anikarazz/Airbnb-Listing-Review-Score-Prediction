# Airbnb-Listing-Review-Score-Prediction

This project applies the machine learning lifecycle to solve a predictive modeling problem using the **Airbnb NYC listings dataset**. The goal is to predict whether a listing will receive a **high review score (≥ 4.5)** based on listing and host features.

---

## 📊 Problem Definition

- **Dataset:** Airbnb NYC listings data (`airbnbListingsData.csv`)  
- **Prediction Goal:** Will a listing receive a high rating?  
- **Label:** `high_rating` (1 if review score ≥ 4.5, else 0)  
- **Problem Type:** Supervised learning → Binary classification  

**Features Considered:**
- Price  
- Availability (`availability_365`)  
- Host attributes (e.g., superhost status, response rate, acceptance rate)  
- Number of reviews & reviews per month  
- Neighbourhood group  

### Why This Problem Matters
Accurate predictions of high-rated listings can help Airbnb:
- Highlight quality listings at the top of search results  
- Provide insights to hosts on how to improve  
- Enhance guest satisfaction and trust in the platform  

---

## Project Workflow

1. **Data Loading & Cleaning** — Load the dataset and prepare it for analysis  
2. **Exploratory Data Analysis (EDA)** — Understand trends, distributions, and feature relationships  
3. **Feature Engineering** — Create and refine features for model input 
4. **Model Training** — Train classification models (e.g., logistic regression, decision trees) 
5. **Model Evaluation** — Assess performance using metrics such as accuracy, precision, recall, and F1 score  
6. **Model Improvement** — Tune hyperparameters and improve model results  
