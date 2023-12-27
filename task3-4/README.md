# 1.Data Preprocessing

## * Combining Magnitude and Magnitude Type:
The 'Magnitude' and 'Magnitude Type' columns are combined into a new column named 'Magnitude and Magnitude Type'.

* Removing Columns:
The 'Magnitude Source' column is removed from the dataset.

* Filling Missing Values:
Missing values in specific columns (Depth Error, Magnitude Error, etc.) are filled with zeros.

* Extracting Date Components:
The 'Date' column is parsed to extract the 'Month', 'Day', and 'Year' components.
