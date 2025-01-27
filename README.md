# Austin-Housing-Price-Predictor
A project predicting Austin housing prices based on variables like living area size, bedrooms, school ratings, and year built, using **regression models**. This project aims to provide insights for homeowners, real estate investors, and financial institutions to make informed decisions.

## Results
The detailed results, including all code outputs and visualizations, can be accessed through the following link:  
[View the full notebook with visualizations](https://drive.google.com/file/d/1QRE4HaWTMqIztSZLyIJ7KFyqBUeTuyTg/view?usp=sharing)

## Introduction
This project explores the housing market in Austin, Texas, and aims to predict the prices of single-family homes using key variables such as:
- Living area size (square footage)
- Number of bedrooms
- Average school rating
- Year built

The dataset, "Austin, TX House Listings," contains house listing data from 2021. The primary research question is:  
**"Can we predict the housing prices of single-family homes in Austin, Texas, based on the above factors?"**

## Methods
To answer the research question, we employed the following steps:
1. **Data Preprocessing and Filtering**:
   - Removed non-single-family homes from the dataset.
   - Selected relevant predictors: `homeType`, `latestPrice`, `livingAreaSqFt`, `numOfBedrooms`, `avgSchoolRating`, and `yearBuilt`.

2. **Modeling**:
   - Applied K-Nearest Neighbors (KNN) regression to build the predictive model.
   - Split the dataset into training and testing sets.
   - Evaluated model performance using a confusion matrix and visualization techniques.

3. **Visualization**:
   - Plotted variable relationships using `ggplot` and overlayed prediction lines to compare actual and predicted prices.

## Expected Outcomes and Significance
We expect the model to accurately predict housing prices in Austin, providing:
- Insights for homeowners to set fair market values.
- Tools for real estate investors to identify undervalued properties.
- Support for banks and financial institutions in assessing risk for loans.

This project demonstrates the potential for data-driven decision-making in the real estate market. Future extensions could explore additional variables, expand to other property types (e.g., condos, townhouses), or apply the methodology to cities beyond Austin.
