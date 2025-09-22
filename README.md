Internship day 1 task

Steps performed in cleaning the dataset

1 Firstly we will import pandas and NumPy library in Jupiter Notebook

2 Reading csv file netflix_titles.csv using encoding='ISO-8859-1'

3 Checking datatypes

4 Removing columns containing all NaN value

5 Importing datetime from date and changing date column datatype to date

6 Checking nulls in every column

7 Using fillna to change NaN to Not Listed in directors columns as it contains significant values which if removed will reduce the dataset for analysis.

8 Doing with cast and country column same using fillna.

9 Removing date with nulls because it has no significant values.

10 Column duration has mixed categories like season and minutes. Separating both and creating two columns.

11 Filling empty cells with 0 in both columns using fillna.

12 Saving files in excel format.

13 Opening file in excel and changing and checking for datatypes if any.
