# Nexthike_Project03
Exploratory Data Analysis on Housing data using Python.

About:-
There are so many variables that impact the price of a house. With dynamic parameters in the residential real estate business, reaching a reasonable price for better business opportunities is always important. As a part of the analytics team in a real estate company, you have to come up with the variables that impact the house's price through analyzing and visualizing the data.

Data Overview:-
The data i used for the EDA is a housing price data set, and the data set having 1460 rows and 81 columns with Numeric and Categorical and Temporal Variables (Datetime variables) with the Target variable "SalePrice". Some important features like- Neighborhood, HouseStyle, Overall Quality, Overall Condition, Garagarea, Garagecars, Yearbuilt, TotalBsmtSF, GarageYrbuilt, YearRemodAdd, 1stFlrSF, GrLivArea, FullBath, Condition1, Condition2, ExterQual.
The data has many missing values and outliers.

Project Goal:-
1. Explore the Housing Price Dataset.
2. Analyze and Visualize the dataset with various plots and graphs.
3. By performing EDA we have to check and conclude that which variables are impacting the house's price.

Methods and Analysis:-
1. Python Libraries Used - Numpy, Pandas, Matplotlib, Seaborn in the Jupiter Notebook Environment.
2. Examined the structure of the dataset, Including the number of Rows and Columns, Checked for missing values and decided on a strategy for handling them.
3. Identifying the types of variables (Numerical, Categorical, Temporal etc.)
4. Computing summary statistics for numerical variables (Mean, median, mode, Std Deviation, min, max etc.)
5. Explored the distribution of numerical features using histogram, scattered, bar and kernal density plots and line plots.
6. Univariate analysis, Multivariate analysis using count plot, scatter, crosstab grouped bar chart, heatmap, boxplot, swarmplot and violin plots.
7. Correlation analysis- Calculated and Visualized correlation between numerical features, Used a heatmap to identify strong relationships.

Conclusion:-
With all the different graphs and plots and EDA techniques we applied on the Housing Price Dataset, we observed that the 'OverallQual', 'GrLivArea', and 'TotalBsmtSF' are strongly correlated with SalePrice.

'Neighborhood', 'HouseStyle','GarageCars' and 'GarageArea' are also correlated variables. As these change they also affect the price of the house in a positive manner.







