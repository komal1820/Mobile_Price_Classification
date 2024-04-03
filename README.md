# Mobile_Price_Classification

This repository contains the code and analysis for a project investigating data-driven mobile phone pricing strategies for Mobilitas Inc., a new mobile phone startup.

# Project Overview

Mobilitas aims to disrupt the mobile phone market by offering high-quality, competitively priced smartphones. This project leverages historical mobile phone sales data to understand the relationship between phone features and pricing. These insights will inform Mobilitas' product development and pricing strategies.

# Data

The project utilizes a dataset containing information on over 2,000 mobile phone models from various manufacturers. The data includes features like RAM, battery power, screen resolution, and price range etc.

**Kaggle Dataset:** [ https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification/data?select=train.csv](url)

# Analysis

The project employs various machine learning techniques, including:

**Decision Trees** to identify key features influencing price range.

<img width="461" alt="Screenshot 2024-04-03 at 5 59 45 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/5496ce0a-8e97-40c9-aab4-65cdf4140e1f">


**Logistic Regression** to model the probability of a phone belonging to a specific price range based on its features.

<img width="786" alt="Screenshot 2024-04-03 at 6 03 53 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/d4152657-1899-4999-a320-c9a568740b74">

**Support Vector Machines (SVM)** to classify phones into different price ranges.

<img width="468" alt="Screenshot 2024-04-03 at 6 02 28 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/6f8cb93b-84fe-4993-bc1c-5b8bf3f121d5">

**Linear Regression** to analyze the relationship between price range and battery power.

<img width="784" alt="Screenshot 2024-04-03 at 6 02 15 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/22294bee-06b1-4fc1-b8e6-566509e5e5c4">

**ROC**


<img width="758" alt="Screenshot 2024-04-03 at 6 01 20 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/acad29c4-0998-4ba0-9a55-945761df8882">
<img width="757" alt="Screenshot 2024-04-03 at 6 01 28 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/0c5fbb13-b1a8-4118-bcc5-77369dc824ba">
<img width="801" alt="Screenshot 2024-04-03 at 6 01 36 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/c8673d1c-7735-4723-8674-ebacfe14831b">
<img width="760" alt="Screenshot 2024-04-03 at 6 02 04 PM" src="https://github.com/komal1820/Mobile_Price_Classification/assets/69956556/433ffabc-3a82-44f6-b9d8-484158f39efd">

# Technologies Used

**RStudio -** A powerful open-source integrated development environment (IDE) for R programming, used for data manipulation, statistical analysis, and visualization.

**RapidMiner -** An enterprise-grade data science platform used for data preparation, machine learning model building, and model evaluation.

# Results

The analysis revealed significant relationships between phone features and pricing. Notably, features like RAM, battery power, and screen resolution were identified as key determinants of price range.

# Future Work

• Explore incorporating broader market data and consumer behavior analysis.

• Investigate additional features and their impact on pricing.

• Refine the models for more accurate price predictions.

# Running the Code

This repository includes Jupyter notebooks for data analysis and model development. The notebooks require specific libraries to be installed. Refer to the individual notebooks for details.

# Conclusion

This project demonstrates the potential of data analytics to inform mobile phone pricing strategies. The findings provide valuable insights for Mobilitas Inc. and contribute to the understanding of feature-based pricing in the mobile phone industry.
