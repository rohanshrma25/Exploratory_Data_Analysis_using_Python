# Sales Dataset Exploratory Data Analysis (EDA)

This Python project conducts exploratory data analysis (EDA) on a sales dataset using data analysis libraries such as pandas, numpy, matplotlib, and seaborn. The goal of this project is to gain insights into the sales data through visualizations and statistical analysis.

## Installation

To run the project locally, ensure you have Python installed along with the necessary libraries. You can install the required libraries using pip:  

```
pip install pandas numpy matplotlib seaborn scipy.stats
```
  
## Data  

The dataset used in this analysis is stored in 'Sales_dataset1.xlsx'. It contains information about sales transactions, including customer demographics, product details, purchase types, payment methods, and sales amounts.  
  
## Data Preprocessing:  
  
* Correcting data types  
* Handling missing values  
* Removing duplicates  
* Analysis  
  
The analysis includes the following steps:  
  
1. Univariate Analysis:  
  
* Age-Density plot 
* Preferred payment methods    
* Top customer countries  
  
2. Bivariate Analysis:
  
* Total sales by gender  
* Profit trends over time  
  
3. Multivariate Analysis:  
  
* Correlation matrix  
* Total sales by product type and gender

## Hypothesis Testing
**Test 1**: Is there a significant difference in the average total sales between male and female customers?
- Statistical Test: 2-sample t-test

**Test 2**: Is there a significant difference in average total sales across different payment methods?
- Statistical Test: ANOVA test
  
## Files Included  
EDA_Project.py: Main Python script for data analysis.  
Sales_dataset1.xlsx: Sales dataset used in the analysis.  
README.md: Project documentation.  
  
## Contributing  
Contributions to this project are welcome! If you have any suggestions, bug reports, or feature requests, feel free to open an issue or submit a pull request.  

## Acknowledgements  
Special thanks to the creators of pandas, numpy, matplotlib, and seaborn for their invaluable contributions to the data analysis ecosystem.
