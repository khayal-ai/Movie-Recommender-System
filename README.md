# 🎬 Movie Recommendation System using Machine Learning 🍿🎬

## Overview
This project implements a **content-based movie recommendation system** using **Machine Learning (K-Nearest Neighbors)**.  
Movies are recommended based on **genre similarity** between user preferences and available movies.

The system is trained using **genre feature vectors** and recommends movies using **cosine similarity**.

---

## Features
- Content-based movie recommendation
- Trained ML model using **KNN**
- One-hot encoding of movie genres
- User-defined genre input
- Functional testing & qualitative evaluation
- Visualizations for result analysis

---

## Methodology
1. Load movie dataset  
2. Preprocess data and handle missing values  
3. Convert genres into numerical feature vectors  
4. Train KNN model using cosine distance  
5. Take user genre input  
6. Predict similar movies using trained model  
7. Rank and display recommendations  
8. Evaluate results using functional testing  
9. Visualize recommendations  

---

## Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  

---

## Dataset
- **movies.csv**
- Columns used:
  - `title`
  - `genres`
  - `vote_average`
  - `vote_count`

Missing genre values are handled before processing.

---

## Installation & Setup

```bash
pip install pandas scikit-learn matplotlib

 




