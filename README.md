# Car Data Analysis and Price Prediction

## Project Overview

This project analyzes a car dataset containing various attributes such as brand, model, engine specifications, fuel efficiency, and pricing (MSRP). The goal is to:

- Explore and visualize key aspects of the dataset  
- Identify the most fuel-efficient cars  
- Investigate relationships between engine characteristics and MSRP  
- Build a simple predictive model to estimate car prices based on engine features  
- Detect potentially overpriced cars based on this model  

## Dataset

The dataset includes the following important columns:

- **Make**: Car brand  
- **Model**: Car model  
- **Vehicle Size**: Vehicle size category (Compact, Midsize, Large, etc.)  
- **Transmission Type**: Type of transmission (Automatic, Manual, etc.)  
- **Engine HP**: Engine horsepower  
- **Engine Cylinders**: Number of engine cylinders  
- **city mpg**: Fuel efficiency in city driving (miles per gallon)  
- **highway MPG**: Fuel efficiency on highways (miles per gallon)  
- **MSRP**: Manufacturer’s Suggested Retail Price  

## Key Features and Analyses

1. **Fuel Efficiency Analysis**  
   - Computed combined MPG as the average of city and highway MPG  
   - Identified top 5 most fuel-efficient cars (unique Make and Model combinations)  
   - Visualized these cars using horizontal bar plots  

2. **Engine and Price Relationship**  
   - Explored scatter plots between engine horsepower, cylinders, and MSRP to observe trends  
   - Used simple linear regression on engine horsepower and cylinders to predict MSRP  

3. **Price Prediction and Overpriced Cars Detection**  
   - Trained a linear regression model using engine HP and cylinders to estimate MSRP  
   - Calculated differences between actual MSRP and predicted MSRP  
   - Identified top 10 potentially overpriced cars based on the largest positive difference  

## How to Run

1. **Prerequisites**  
   - Python 3.x  
   - Packages: `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `tabulate`  

   Install required packages via pip:  
   ```bash
   pip install pandas matplotlib seaborn scikit-learn tabulate
