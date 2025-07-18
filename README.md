TikTok Content Moderation: Claim vs. Opinion Classification
Project Overview
This project focuses on developing a machine learning pipeline to distinguish between factual claims and personal opinions in over 19,000 TikTok videos. The goal is to support content moderation by flagging potentially misleading or unverifiable content, thereby enhancing platform trust and user safety.

Objectives
Identify and classify TikTok content as either a claim or an opinion.

Improve moderation accuracy and efficiency through data-driven policy insights.

Visualize content trends to support strategic moderation decisions.

Key Features
Data Cleaning & Preprocessing

Removed null values and standardized missing fields

Normalized text (e.g., case folding, punctuation removal, tokenization)

Engineered new features for model input (e.g., word count, presence of hashtags)

Machine Learning Pipeline

Models used: Logistic Regression, Random Forest, XGBoost

Managed imbalanced dataset using class weights and resampling techniques

Evaluated models with precision, recall, and F1 score

Data Visualization & Insights

Used Seaborn and Matplotlib to explore patterns by:

Verification status

Engagement metrics (likes, shares, comments)

Claim types

Derived moderation policy recommendations based on these insights

Tools & Libraries
Python

Pandas, NumPy – Data manipulation and preprocessing

Scikit-learn, XGBoost – Machine learning

Seaborn, Matplotlib – Data visualization

Results
Successfully classified content with high precision and recall, especially for minority (claim) classes.

Identified high-risk patterns in content that receives disproportionate engagement.

Delivered actionable recommendations to improve moderation workflows based on data trends.

Potential Impact
By automating the classification of claims vs. opinions, this project can serve as a prototype for large-scale social media moderation tools, aiding trust & safety teams in reducing misinformation spread while preserving freedom of expression.
