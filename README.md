# Elevate Labs AI & ML Internship - Task 1
## Project Objective
Data Cleaning and Preprocessing on the Titanic Dataset using Python and Pandas.
## Preprocessing Steps Completed
1. **Data Inspection:** Loaded the raw data directly from a public URL to check feature shapes and data types.
2. **Missing Value Management:** Cleaned the missing fields by filling `Age` with its median value, `Embarked` with its mode, and dropping the highly incomplete `Cabin` column.
3. **Categorical Variable Mapping:** Handled the `Sex` column by converting textual categories into binary integers (`male: 0`, `female: 1`).
4. **Feature Scaling:** Applied `StandardScaler` to level the numeric scales of both `Age` and `Fare`.
5. **Outlier Mitigation:** Filtered out 116 extreme passenger fare anomalies using the Interquartile Range (IQR) method.
