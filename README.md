# Data-Cleaning

Select a dataset with missing values (e.g., Titanic, Diabetes, Housing).
Identify and:
Remove or fill missing values using fillna() or SimpleImputer
Detect and drop duplicates
Correct inconsistent types (e.g., convert object to numeric)

df = pd.read_csv('dataset.csv')
df.drop_duplicates(inplace=True)
df['column'] = pd.to_numeric(df['column'], errors='coerce')
