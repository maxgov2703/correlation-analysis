# Correlation Analysis: Car Weight vs Fuel Efficiency

## Project Description

This project investigates the relationship between car weight and fuel efficiency (MPG) using statistical correlation analysis.

The goal of the analysis is to determine whether heavier cars tend to consume more fuel and to evaluate the strength and statistical significance of this relationship.

The project includes:

- Exploratory Data Analysis (EDA)
- Visualization of relationships between variables
- Calculation of correlation coefficients
- Statistical significance testing
- Linear regression visualization

## Dataset

The dataset contains technical characteristics of automobiles such as engine size, weight, horsepower, and fuel efficiency.

Key features include:

- mpg — fuel efficiency (miles per gallon)
- cylinders — number of cylinders
- displacement — engine displacement
- horsepower — engine power
- weight — vehicle weight
- acceleration — acceleration performance
- model_year — year of production
- origin — region of manufacture

Dataset size:

- 398 observations
- 9 features

## Project Structure

correlation_analysis
│
├ dataset
│   └ auto_mpg_dataset.csv
│
├ plots
│   ├ weight_vs_mpg_scatter.png
│   └ weight_vs_mpg_regression.png
│
├ correlation_analysis.ipynb
└ README.md

## Exploratory Data Analysis

The analysis begins with data inspection and cleaning.

Steps include:

- checking dataset structure
- identifying missing values
- selecting numerical variables for analysis
- visualizing relationships between variables

## Visualization

### Scatter Plot: Weight vs MPG

The scatter plot shows a visible negative relationship between vehicle weight and fuel efficiency.

Heavier vehicles tend to have lower MPG values.

### Regression Plot

The regression line confirms a negative linear relationship between the variables.

## Correlation Analysis

Three correlation metrics were calculated:

Pearson correlation: -0.83  
Spearman correlation: -0.88  
Kendall correlation: -0.69  

Interpretation:

- All coefficients indicate a strong negative relationship.
- As car weight increases, fuel efficiency decreases.

## Statistical Significance

Statistical tests confirm that the observed relationship is significant.

Pearson p-value: 6.0e-102  
Spearman p-value: 2.6e-125  
Kendall p-value: 5.8e-92  

Since p-value < 0.05, we reject the null hypothesis and conclude that the correlation is statistically significant.

## Key Findings

The analysis shows that:

- Vehicle weight strongly influences fuel efficiency.
- Heavier cars consume more fuel.
- The relationship is statistically significant across multiple correlation methods.

## Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- SciPy
- Google Colab

## How to Run the Project

Clone the repository:

git clone https://github.com/your_username/correlation_analysis.git

Install required libraries:

pip install pandas numpy matplotlib seaborn scipy

Run the notebook:

correlation_analysis.ipynb

## Future Improvements

Possible extensions of this analysis:

- Multiple regression analysis
- Feature importance analysis
- Fuel efficiency prediction model
- Analysis of additional vehicle characteristics
