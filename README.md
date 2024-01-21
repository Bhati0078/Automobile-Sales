# Automobile-Sales

### Summary
- Cleaned and preprocessed the dataset.
- Handled missing values and converted '?' to NaN.
- Replaced 'num-of-doors' values with numerical equivalents.
- Identified and extracted the most expensive car's make and price.
- Added a new column 'No. of doors' based on the number of doors.
- Imputed missing values in 'stroke' with 0.
- Created a new DataFrame showing the count of cars for each make.
- Introduced a new column 'Update_price' based on the engine location.
- Sorted the DataFrame by 'make' and 'price'.

### Changes Made
1. Checked for missing values in the 'normalized-losses' column and replaced 'NaN'.
2. Replaced all '?' values in the DataFrame with NaN using the replace method.
3. Converted 'num-of-doors' values to numerical format (two -> 2, four -> 4, '?' -> 0).
4. Extracted the most expensive car's make and price, storing them in 'company_name' and 'price' variables.
5. Added a new column 'No. of doors' based on the 'num-of-doors' values.
6. Checked unique values in the 'num-of-doors' column.
7. Converted the 'price' column to float type and identified the most expensive car using loc.
8. Created a DataFrame showing the maximum prices for each car make.
9. Created a DataFrame showing the maximum horsepower for each car make.
10. Filled missing values in the 'stroke' column with 0.
11. Checked unique values in the 'make' column and created a DataFrame showing the count of cars for each make.
12. Introduced a new column 'Update_price' based on the engine location.
13. Sorted the DataFrame by 'make' and 'price'.

### Additional Information
- Checked and confirmed the shape of the DataFrame.
- Used the value_counts method to get a count of each car make.
- Utilized the fillna method to handle missing values in the 'stroke' column.
- Checked unique values in the 'num-of-doors' column before and after replacement.
- Calculated the most expensive car using the max() method on the 'price' column.

---

