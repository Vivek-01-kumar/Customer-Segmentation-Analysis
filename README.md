Objective: Segment customers based on purchasing behavior and demographics to better understand their characteristics.

Dataset: Loaded from a CSV file named ifood_df.csv.

Libraries Used: pandas, numpy, seaborn, matplotlib, sklearn.

Data Cleaning: Removed unnecessary columns like Z_CostContact and Z_Revenue; checked for missing values and data types.

Exploratory Data Analysis (EDA):

Histograms for Income and Age.

Analysis of demographic attributes like income, age, number of children at home, and marital status.

Feature Engineering: Combined and grouped columns (e.g., total amount spent on products).

Clustering: Applied KMeans clustering after standardizing features to identify distinct customer groups.
