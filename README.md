# Data-Cleaning-In-SQL

# Overview

This project focuses on cleaning and standardizing the Nashvile Housing dataset. The SQL quires address issues such as standardizing date formats, populating missing property addresses, braking down addresses into individual columns, and normalizing 'SoldASVacant' values. The cleanng process involves handling duplicates and removing unused columns for a more refined dataset.

# Project Structure

# 1.Standardize Date Format
- Converts the 'SaleDate' column to a standardized date format.

# 2.Populate Property Address Data
- Populates missing property addresses by updating null values based on ParcelID.

# 3.Break Out Property Address into Individual Columns
 - Splits the 'PropertyAddress' column into 'PropertySplitAddress' and 'PropertySplitCity'.

# 4.Break Out 'OwnerAddress' column into Individual Columns
 - Uses parsename to split 'OwnerAddress' into 'OwnerSplitAddress', 'OwnerSplitCity', and 'OwnerSplitState'.

# 5.Change 'Y' and 'N' to 'Yes' and 'No' in 'SoldAsVacant' Field.
- Updates the 'SoldAsVacant' column to replace 'Y' with 'Yes' and 'N' with 'No'.

# 6.Remove Duplicates
 - Identifies and displays duplicate records based on specific columns.

# 7.Delete Unused Columns
 - Drops columns 'OwnerAddress', 'TaxDistrict', 'PropertyAddress', and 'SaleDate' to streamline the dataset.

# Screenshots of the SQL Quries

# 1. Original 'SaleDate' column

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/42a7b87f-55f1-4839-be7b-cf54248f7f86)

# Converted 'SaleDate' column

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/9cde4eb7-7af5-407d-944a-466189a0a6a5)

# 2.PropertyAddress column With Null values  (Row -532 & Row-534)

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/f04e359c-6f9f-4dd0-9792-0a7a137a7de5)

# PropertyAddress column after removing Null values (Row-532 & Row-534)

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/96248a76-676f-4b3e-8f41-c4c51f8c68e4)

# 3.PropertyAddress column split into PropertySplitAddress and PropertySplitCity

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/d43e0184-7228-463c-9f5d-4910b00bf581)

# 4.Spliting 'OwnerAddress' column into 'OwnerSplitAddress', 'OwnerSplitCity', and 'OwnerSplitState'.

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/95056a2e-2303-4b04-aecf-0df9d1b17381)

# 5.Original 'SoldAsVacant' column with 'N' and 'Y' values

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/560d63b8-6e4f-49cc-aec9-5e16dae5afa2)

# Converted 'N' into 'No' and 'Y' into 'Yes'.

![image](https://github.com/nsultana5/Data-Cleaning-In-SQL/assets/98044004/2aeb0d49-af4c-4955-823f-8bab39a04b4d)

# Usage 

- 1.Execute the SQL queries in the specified order on your SQL environment.
- 2.Explore the cleaned Nashville Housing dataset with refined structure and standardized values.

# Dataset
 - Dataset Link:https://www.kaggle.com/datasets/tmthyjames/nashville-housing-data
 - The project utilizes the Nashville Housing dataset.







