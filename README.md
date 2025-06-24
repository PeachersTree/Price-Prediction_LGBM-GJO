# Improved LightGBM Based on Golden Jackal Optimization for Airbnb Price Prediction

## Overview  
This project explores various aspects of Airbnb listings in Washington, D.C. using publicly available data from Inside Airbnb. The main focus is to build a price prediction model using LightGBM, and improve it using Golden Jackal Optimization (GJO) for hyperparameter tuning.

All development was conducted in Python using VS Code and Jupyter Notebook, and the research is limited to listings in Washington, D.C.


## Objectives  
1. Apply and evaluate the LightGBM model performance in predicting the price of Washington, D.C. Airbnb listings.  
2. Apply and evaluate the performance of hyperparameter tuning using Golden Jackal Optimization, and compare the model's performance before and after optimization.  
3. Analyze the contribution of each feature in influencing the model’s predictions.


## Significance  
### For Airbnb  
Provides insight into various factors that influence rental pricing, which can inform market strategies, improve host relationships, and support feature development.

### For Hosts or Potential Hosts  
Helps hosts understand how factors such as amenities, room type, and night requirements affect pricing, guiding them in setting competitive and profitable prices.

### For Researchers  
Adds to the literature on technology-based rental platforms, particularly in predictive modeling and optimization, and contributes to broader research on the digital economy.


## Limitations  
1. The model is limited to Washington, D.C., and may not generalize to other regions.  
2. The listing data covers the period from May 10, 2009 to September 16, 2024, and was scraped on September 17, 2024 by Inside Airbnb.  
3. The model uses 15 selected variables out of 75 available in the dataset.  
4. The primary method is LightGBM, with Regression Tree used as a comparison.  
5. Model performance is evaluated using:  
   - Mean Squared Error (MSE)  
   - Root Mean Squared Error (RMSE)  
   - Mean Absolute Error (MAE)  
   - R-squared (R²)  
6. The entire project was implemented in Python, using VS Code and Jupyter Notebook.


## Tools  
- Language: Python  
- Libraries: `lightgbm`, `scikit-learn`, `pandas`, `numpy`, `matplotlib`, `seaborn`, etc 
- Optimization: Custom implementation of Golden Jackal Optimization  
- IDE: Visual Studio Code (with Jupyter extension)


*Due to various reasons, the review data and sentiment analysis results are not published here*
