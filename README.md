# ML project one

### Imported Titanic dataset using NumPy, Pandas, Matplotlib, and Seaborn.

- Loaded data with pd.read_csv().

- Used head() to show first 5 rows and tail() for last 5 rows.

- Checked data types and structure with info().

- Got numeric summary statistics using describe().

- Displayed dataset size with df.shape.

- Detected missing values using df.isnull().sum().

- Removed rows with missing values using df.dropna().

- Filled missing 'Age' values with the mean of the column using fillna().

- Filled missing 'Cabin' values with the most frequent category (mode).

- Converted categorical columns to numeric using LabelEncoder.

- Normalized numeric columns to [0,1] range with MinMaxScaler.

- Standardized data to have mean 0 and standard deviation 1 using StandardScaler.

- Created boxplots for all numeric columns with Seaborn and Matplotlib.

- Defined remove_outliers_iqr(df) function to remove outliers from numeric columns based on the Interquartile Range (IQR) method.