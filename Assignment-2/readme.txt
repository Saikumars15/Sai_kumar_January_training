1.Missing Value Imputation: Missing values in 'Square_Footage' were imputed with the median, 'Year_Built' with the mean, and 'Internal_Code' with the mode. The 'City' column also had its missing values handled.
2.Data Type Conversion: The 'Year_Built' column was successfully converted to an integer data type.
3.Outlier Treatment: Outliers in 'Square_Footage', 'Price', and 'Distance_to_Center' were detected and treated using the IQR method (capping values at the upper and lower bounds).
4.Duplicate Removal: The dataset was checked for duplicate records, and none were found, confirming no duplicates needed to be removed.
5.Irrelevant Column Dropping: The 'House_ID' and 'Internal_Code' columns were dropped as they were identified as irrelevant for the analysis.
