**Project Overview**

This project involves a regression analysis of real estate data to help a local real estate investor make data-driven decisions. The goals were to:
- Identify factors influencing home sale prices.
- Predict the sale prices of five specific homes the investor plans to sell in 2011.
- Provide actionable recommendations for the investor based on the analysis.

Deliverables:
- PowerPoint Presentation: A visual summary of the analysis and results, including recommendations.
- Jupyter Notebook: Code used for data preparation, analysis, and modeling.

**Files**

**1. PowerPoint Presentation**
- File: Factors of Real Estate Prices.pptx
- Purpose: Summarizes key findings, methodology, and actionable recommendations for the real estate investor.

Key Highlights:
- Data Overview: Analysis of 1,455 homes sold between 2006-2010 (after removing outliers).
- New variable created: Total_SF, combining basement, first-floor, and second-floor square footage.
- Adjusted CentralAir variable to HasCentralAir for binary analysis.

Regression results and interpretations:
- 77.8% of the variation in sale price is explained by the model.
- Key variables include Total_SF, HasCentralAir, FullBath, and YearBuilt.
- Recommendations include focusing on newer, more spacious homes with central air and multiple bathrooms.

**2. Data Files**
- homesforsale.csv: Contains information on five homes for which sale price predictions were required.
- Housing_Prices_24.csv: The main dataset used for regression analysis, including 1,460 rows of real estate data.

**3. Jupyter Notebook**
- File: real_estate.ipynb
- Purpose: Documents the entire analytical workflow, including:
    - Data cleaning and preprocessing.
    - Exploratory data analysis (EDA).
    - Model building and evaluation.
    - Prediction of sale prices for 2011 homes.

Key Features:
- Clearly annotated code for each step.
- Variable transformations and treatment of outliers.
- Visualization of residuals and key variable relationships.
- Iterative regression modeling process to optimize performance.
