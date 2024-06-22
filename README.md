# Stats-and-data-handling

## Loading the Data:

### Loaded the Titanic dataset and displayed the first few rows.
## Data Cleaning:

## Removed duplicate rows.
### Handled outliers using the Z-score method, keeping rows where all numeric feature Z-scores are less than 3.
### Corrected data types for columns if necessary.
## Transformation:

### Applied logarithmic and square root transformations to the 'Fare' column.
## Normalization:

### Used MinMaxScaler to normalize 'Fare' and 'Age' columns to the range [0, 1].
## Standardization:

### Used StandardScaler to standardize 'Fare' and 'Age' columns to zero mean and unit variance.
## Encoding:

### Applied One-Hot Encoding to the 'Embarked' column.
### Applied Label Encoding to the 'Sex' column.
## Imputation:

### Filled missing values in 'Age' and 'Fare' columns with their respective means.
## Handling Missing Data:

### Dropped rows that contain any missing values.
## Dimensionality Reduction:

### Applied PCA to reduce the dataset to 2 components.
## Data Integration:

### For demonstration, combined the DataFrame with itself.
## Sampling:

### Randomly sampled 100 rows from the DataFrame.
### This script demonstrates a range of data preprocessing techniques, providing a solid foundation for preparing data for analysis or machine learning tasks.
