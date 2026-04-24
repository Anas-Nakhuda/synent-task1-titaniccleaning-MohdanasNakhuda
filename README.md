# Titanic Dateset Cleaning for Analysis-Task1

## Main Aim is to preprocess the raw data for Analysis which contains dealing with missing values,removing duplicates,converting datatypes and renaming necessary columns.

# Dataset Details
-**Source**: Kaggle Titanic Dataset
-**Format**: CSV

# Approach
-**Missing Values**: filled 'Age' with median and 'Embarked' with mode,drop the 'Cabin' column due to more missing values.
-**Duplicates**: remove duplicates using 'df.duplicated()'.
-**Datatypes**: Converting 'Survived' to bool ,'Age' to int , 'Sex' and 'Embarked' to category types.
-**Renaming Columns**: renaming columns 'Pclass' to 'Passenger_Class','SibSp' to 'Siblings_Spouse','Parch' to 'Parents_Children' for clarity and readaility.

# Result
Titanic Dataset is ready for Analysis.
