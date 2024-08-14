# Crime Category Prediction Challenge

## Overview

The Crime Category Prediction Challenge is a machine learning project aimed at predicting the type of crime based on various features related to crime incidents. The dataset includes information about crime locations, victim demographics, and other factors.

## Dataset

The dataset consists of the following files:

- `train.csv`: Training set with the target variable `crime_category` and feature attributes.
- `test.csv`: Test set with similar feature attributes but without the `crime_category` column.
- `sample.csv`: A sample submission file in the correct format for competition submissions.

### Features

The dataset includes the following columns:

1. `Location`
2. `Cross_Street`
3. `Latitude`
4. `Longitude`
5. `Date_Reported`
6. `Date_Occurred`
7. `Time_Occurred`
8. `Area_ID`
9. `Area_Name`
10. `Reporting_District_no`
11. `Part 1-2`
12. `Modus_Operandi`
13. `Victim_Age`
14. `Victim_Sex`
15. `Victim_Descent`
16. `Premise_Code`
17. `Premise_Description`
18. `Weapon_Used_Code`
19. `Weapon_Description`
20. `Status`
21. `Status_Description`
22. `Crime_Category` (Target Variable)

### Encoding

The `Crime_Category` feature is encoded as follows:

- `0`: Crimes against Persons
- `1`: Crimes against Public Order
- `2`: Fraud and White-Collar Crimes
- `3`: Other Crimes
- `4`: Property Crimes
- `5`: Violent Crimes

## Project Structure

- `data/`: Contains the dataset files.
- `src/`: Source code for data preprocessing, model training, and evaluation.
- `notebooks/`: Jupyter notebooks for exploratory data analysis and experimentation.
- `README.md`: This file.

## Setup

1. **Clone the Repository**

   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```
   
