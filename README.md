# R-NYC-Airbnb-Analysis
Exploratory analysis and linear regression pricing model for 48K+ NYC Airbnb listings in R
NYC Airbnb Market Analysis — R
Exploratory data analysis and linear regression modeling of New York City Airbnb listings, built for MSBA 615 (R for Analytics).
Overview
This project analyzes 48,000+ NYC Airbnb listings to identify pricing patterns across boroughs, room types, and availability. Includes data cleaning, outlier detection, visualization, and a predictive pricing model.
What I Built

Cleaned and preprocessed raw listing data: removed redundant columns, handled zero-price records, detected outliers using IQR method
Built exploratory visualizations (histograms, box plots, bar charts) across pricing, availability, room type, and borough dimensions
Trained a linear regression model to predict listing price from reviews, availability, room type, and neighborhood
Analyzed model fit and identified limitations (R² = 0.46), with recommendations for additional features

Tools

R (dplyr, ggplot2, tidyverse, gridExtra)
RMarkdown

Key Findings

Manhattan and Brooklyn dominate listings; entire home/apartment listings command significantly higher prices
Over half of NYC listings have zero availability, reflecting high demand
Room type and borough are the strongest predictors of price; model suggests additional features (square footage, transit proximity) would improve accuracy

Education
M.S. Business Analytics, University of Louisville (2026) | 4.0 GPA
