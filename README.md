# Data Analysis on FBI Times Series Data

## Problem Statement

* The FBI Crime investigation project is strategic initiative to harness the power of data analytics to detect crime patterns and improve public safety.
* To anticipate crime trends, allocate resources strategically and implement proactive measures to prevent criminal activities

## Data Summary
 * The data size : 55.5 MB
 * Shape of the data : 474565,13 
 * Missing values : 150234

## Data Cleaning 

### Handling Missing Valus

* Missing Data is dealt with using polynomial interpolation for numerical data.
* Missing Data is handled by mode for categorical columns

### Handling Outliers 

* Filtering the data by keeping values greater than the lower bound and less than the upper bound, based on the Interquartile Range (IQR) method to remove outliers in the numerical data.

## Feature Engineering:
* Added two new columns, “Day_Night” To analyse the crime activity by day and night
*  “Dayofweek” - to check for the weekday in which the crime occurs

## Data Analysis

 ### Different Crime Types

 ![Image](https://github.com/user-attachments/assets/c9bc3d9a-f84e-4e98-ac3f-17ca5e011301)





