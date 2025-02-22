# basic-eda-ml
This repo will show basic EDA's we can perform to get idea about the dataset

	•	df.info() → Check data types & missing values.
	•	df.describe() → Summary stats (mean, median, min, max).
	•	df.shape → Number of rows & columns.

 Missing Values Handling
 
 	•	df.isnull().sum() → Count missing values.
	•	Fill (df.fillna(value)) or drop (df.dropna()) missing data.

 Duplicate Removal

 	•	df.duplicated().sum() → Count duplicate rows.
	•	df.drop_duplicates() → Remove duplicates.

 Data Type Conversion

 	•	df.dtypes → Check column data types.
> df['date'] = pd.to_datetime(df['date']) <br>
> df['age'] = df['age'].astype(int)
