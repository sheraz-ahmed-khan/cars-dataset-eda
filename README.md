# Cars Data Analysis

## Project Overview

This project analyzes cars dataset containing various attributes such as brand, model, engine specifications, fuel efficiency, and pricing (MSRP). The goal is to:

- Explore and visualize key aspects of the dataset  
- Identify the most fuel-efficient cars  
- Investigate relationships between engine characteristics and MSRP  
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

3. **Overpriced Cars Detection**  
   - Identified top 10 potentially overpriced cars based on the largest positive difference  

## Usage

- Load your car dataset into a pandas DataFrame (`df`)  
- Run the provided Python scripts/notebooks to perform analysis, visualization, and prediction  
- Review outputs and plots for insights  


## Author

[Sheraz Ahmed Khan]  
[sheraz.ahmed@upc.edu]
