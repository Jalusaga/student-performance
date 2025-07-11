# student-performance
> A simple linear regression model for predicting student performace based on multiple variables
This project explores how well we can predict a student’s final grade (G3) in Math (or Portuguese) classes using demographic, social and school-related attributes. We build a simple Linear Regression model and take a look at how accurately it can forecast end-of-term performance.

## 🚀 Project Overview

We load the UCI “Student Performance” dataset, preprocess categorical features, then train a Linear Regression model to predict the final grade (`G3`) based on 21 input features (like study time, family support, past failures, etc.) plus the two ongoing period grades (`G1`, `G2`).  

The goal is to see how close our model’s predictions come to the real scores and evaluate with MSE, MAE, and R².

## 📊 Dataset

- **Source**: [UCI Machine Learning Repository – Student Performance Data Set](https://archive.ics.uci.edu/ml/datasets/student+performance)  
- **File**: `student-mat.csv` (semicolon-separated)  
- **Records**: 395 students  
- **Columns**: 33 total (30 attributes + G1, G2, G3)  

## 🔧 Installation

1. **Clone** this repo:  
   ```bash
   git clone https://github.com/YourUsername/your-repo.git
   cd your-repo

2. **Install** dependencies
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn

## 📈 Results

  - MSE: 3.27
  - MAE: 1.19
  - R²: 0.82

Our linear model explains about 82% of the variance in final grades—pretty solid for such a simple approach!  

## 🤝 Credits & License

  Data source: UCI ML Repository – Student Performance

  Built with ❤️ Alonso Usaga Bonilla

  License: MIT © 2025
