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

![Image](https://github.com/user-attachments/assets/a3ae1533-9397-4925-aa6c-3e8a5e93c504)


 ### Different Crime Types
 

 ![Image](https://github.com/user-attachments/assets/c9bc3d9a-f84e-4e98-ac3f-17ca5e011301)


 * "Theft from vehicle" represents the most prevalent crime category.
	* The high incidence of theft from vehicles suggests the potential effectiveness of implementing enhanced vehicle security measures, such as integrated security systems with automated alerts to law enforcement upon breaches


### Crime Trend Analysis 



![Image](https://github.com/user-attachments/assets/fd80b376-b528-4b25-be03-48dfc9cae828)

*	During the period between 2005 - 2009, the crime rate exhibited a relatively lower frequency, followed by a subsequent increase.
*	The observed reduction in the crime rate can potentially be attributed to implemented crime prevention measures and increased public awareness campaigns


### Geo Spatial Analysis

![Image](https://github.com/user-attachments/assets/f10a7965-91df-41ce-a84b-0d28c76cdda4)



<img width="1012" alt="Image" src="https://github.com/user-attachments/assets/92310454-41e0-459c-80cc-fbda3f0f06b2" />


*	The analysis of crime data indicates that the Central Business District exhibits the highest crime rate among all other neighbourhoods, while Musqueam displays the lowest crime rate
*	Visualizing the crime count per neighbourhood enables the identification of high-crime areas.

## Project Conclusion

•	Strategic law enforcement deployment should prioritize high-crime areas, particularly the “Central Business District” neighbourhood, to enhance public safety.
•	The persistently high incidence of vehicle-related thefts indicates potential security gaps, emphasizing the need for improved vehicle security measures, parking regulations, and public awareness initiatives.
•	Peak crime hours, particularly in the late afternoon and evening, necessitate increased surveillance and targeted patrols, focusing on vehicle-related crimes to mitigate theft.
Law enforcement agencies should implement proactive safety measures, optimize resource allocation, and develop data-driven crime prevention strategies. Additionally, enhancing public awareness of high-crime zones will contribute to improved community security and overall crime reduction


