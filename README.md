# SQL_Employee_Data_
# Introduction
Learning to work with data using SQL has been a fascinating experience. In this repository, I have documented a task from an employee dataset I sourced and downloaded from Kaggle. The dataset contains details about employees from 3 different cities (Bangalore, New Delhi and Pune) and it has 9 columns with thousands of rows.These columns includes employee Education, Joining year, City, Gender, Experience, Payment tier, Leave and Age. The dataset is sampled in the image below.
![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/c36a7c39-bd08-4da6-b3e9-2d862c59aba7)

# Activity
After a moment of getting familiar with the dataset, I checked to see if the dataset has any duplicate values. The code, SELECT DISTINCT (*) FROM EMPLOYEE; was used and it showed that the dataset contained some duplicate values. Also, I coined out some questions that could be answered from the dataset. The following part of this repository contains the questions and actvities carried out in this task.
1. Select the Employee table to show the data where city is Pune and age is between 32 and 40.

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/a201cdf3-0f92-479f-82f4-45c8d770fb8c)

2.  Change the column name ExperienceInCurrentDomain to ExperienceLevel.

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/09af58a5-0977-4c46-9e0c-42f012267797)
![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/30e972dd-ee3b-4d4d-b644-89bd3baff43a)

3. Categorise employees into groups based on their experience level. Here, I started by knowing the range of experience contained throughout the dataset, this happened to be from 0-7.

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/540ea455-50c5-4d1e-955c-671cbe843fe7)

Using the CASE statement, I categorised them into three groups; Entry level, Intermediate and Senior. Then, named the column Experience_Category using the SQL alias function AS.

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/cb7a2bab-5743-4c96-9f74-11a551a4bb9c)

4. Subset the table to show the distribution of male and female employees across the cities.

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/ab1587f9-2f3d-421c-ba37-aa84e08eef11)

5. What Education category has the highest employees?

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/0122eb8f-0de1-49d8-87e5-3a154d150d15)

6. Select the table to show the city with the highest and lowest earners

![image](https://github.com/dianeanalyst/SQL_Employee_Data_/assets/120665115/53a02ace-3d10-4541-89a9-8d1df244899f)

# Conclusion
• There are more male employees than females in all three cities. Factors such as childbirth and maternity leave could be the reason behind having less number of female employees.
#
• Bangalore was seen to have the most employees in the highest and lowest payment tier.
#
• Bachelors degree was the education category with the highest employees. This may be likened to the fact that a bachelors degree forms the backgroung on which all other degrees are built.
#
Working on this task has helped to deepen my understanding on how to sort and filter tables as well as using aggregate functions to carry out data analysis in sql.
