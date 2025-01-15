# Efficient Modeling and Prediction of E-commerce Recommendation Systems: A Case Study on Amazon Product Reviews

## Project Overview

This project explores the predictive potential of e-commerce review data by analyzing Amazon beauty product reviews (2004–2018). It employs machine learning to predict product ratings and builds a recommendation system to provide insights into customer preferences and product popularity.

### Key Features:
- **Rating Prediction**: Binary classification of reviews (5-star vs. 1-4 stars).
- **Recommendation System**: Collaborative filtering based on reviewer-product engagement.
- **Feature Engineering**: TF-IDF vectorization, sentiment scoring, and datetime transformations.
- **Dimensionality Reduction**: Principal Component Analysis (PCA) to improve efficiency and prevent overfitting.

## Team Members
- Yulong Dong
- Daniel Sitompul
- Khanh Thai

## Project Deliverables
- **Research Question**: Can customer reviews predict product ratings?
- **Models Used**: Logistic Regression, Random Forest, and Stacking Models.
- **Performance Metrics**: ROC Curve, AUC, Confusion Matrix, and RMSE.
- **Video Presentation**: [Watch here](https://www.youtube.com/watch?v=JnomNXqTu_8&ab_channel=KhanhThai)

## Dataset

The dataset includes 5.2k reviews from Amazon beauty products, featuring:
- Review Text
- Summary
- Product Style
- Reviewer Information
- Ratings and Votes

**Data Source**: UCSD's open-source Amazon Review dataset.

## Methodology

1. **Exploratory Data Analysis**: Identifying missing data and reviewing feature distributions.
2. **Feature Engineering**:
   - Textual Data: Sentiment analysis and TF-IDF vectorization.
   - Temporal Data: Transforming Unix timestamps to datetime features.
3. **Model Training**:
   - Logistic Regression as baseline.
   - Random Forest for non-linear classification.
   - Dimensionality reduction using PCA.
4. **Recommendation System**: Built using collaborative filtering and Singular Value Decomposition (SVD).

## Key Results

- **Model Performance**:
  - Random Forest outperformed Logistic Regression, achieving an AUC of 0.99.
  - PCA reduced model complexity by 85% while preserving accuracy.
- **Recommendation System**:
  - Provided highly correlated product suggestions based on user-product engagement.

## Contact

For questions or feedback, contact:
- **Daniel Sitompul**: daniel_sitompul@berkeley.edu

---

Let me know if you need further assistance!
