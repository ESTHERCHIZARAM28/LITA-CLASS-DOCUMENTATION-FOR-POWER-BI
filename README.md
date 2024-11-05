# LITA-CLASS-DOCUMENTATION-FOR-POWER-BI

----

## PROJECT TITLE: HR DATA

----

[PROJECT OVERVIEW](#project-overview)

[DATA SOURCES](#data-sources)

[TOOLS USED](#tools-used)

[DATA CLEANING AND PREPARATIONS](#data-cleaning-and-preparations)

[EXPLORATORY DATA ANALYSIS](#exploratory-data-analysis)

[DATA ANALYSIS](#data-analysis)

[DATA VISUALIZATION](#data-visualization)

[INFERENCES](#inferences)

[CONCLUSION](#conclusion)

----

### PROJECT OVERVIEW
This project aims at analyzing the Rate of attrition in the different department and organization at large. it also determine the current working employees.

----

### DATA SOURCES
The primary source of data used in the projects are data.sales.cv and this is an open source data that can be freely downloaded from open source online such as kaggle or FRED or any other data respository site.

----

### TOOLS USED
  
- Power Bi
  
   1. For Data cleaning
  
   2. For Data Analysis
  
   3. For Data visualization
  
   4.creating intereative dashboard.
  
- GitHub for Portfolio Building
      
----

### DATA CLEANING AND PREPARATIONS
In the initial phase of the data cleaning and preparation, the following actions was performed;
   1. Data loading and inspection
   2. Handling missing variables
   3. Data cleaning and formatting
   4. Removing duplicate

----

### EXPLORATORY DATA ANALYSIS
This analysis is meant to answer the followimg questions:
   - The Total number of Employee
   - Attrition Count
   - Rate of Attrition
   - Gender with the highest attrition rate
   - Department with the highest attrition rate

----

### DATA ANALYSIS

- Measures created =
````
 Attriction rate = SUM('HR data'[Attrition Count]) / SUM('HR data'[Employee Count])
````
````
Average Age = AVERAGE('HR data'[Age])
````

----

### DATA VISUALIZATION

- HR TABLE

![image](https://github.com/user-attachments/assets/9f2e541d-74a2-45a0-aecb-5be39b5a59ff)

- HR DASHBOARD

![image](https://github.com/user-attachments/assets/a7ebe032-9352-4f38-bebe-af5c56bfad75)

![image](https://github.com/user-attachments/assets/71aa46a4-79b1-4f22-8226-c4e23ec6fb4e)


##### FILTER BY EDUCATAIONAL FIELD

- HUMAN RESOURCES

![image](https://github.com/user-attachments/assets/fb2d58c1-4de5-4079-b97b-d864d87a1711)

- LIFE SCIENCES

![image](https://github.com/user-attachments/assets/8ddbc174-6cf4-4023-bf76-2e417a1eb6cb)

- MARKETING

![image](https://github.com/user-attachments/assets/fb421986-033c-44a2-9161-a31bb1bbda41)

- MEDICALS

![image](https://github.com/user-attachments/assets/d1b273ed-6c53-4db3-b14c-6c531df7731a)

- OTHERS

![image](https://github.com/user-attachments/assets/2e26cda7-e62f-41e7-9286-f9cba33afa72)

- TECHNICAL DEGREE

![image](https://github.com/user-attachments/assets/417be04b-f958-4668-b523-187d791e1dac)


### INFERENCES
1. ATTRITION RATE BY EDUCATIONAL FIELD: The Human Resources has the highest attrition rate of 26% followed by Technical Degree which have attrition rate of 22%. The Educational field with the lowest attrition rate is Others with attrition rate of 13%.

2.CURRENT EMPLOYEE : Life science has the highest number of current employee of 517, followed by Medicals with current employee of 401. The least is the the Human Resources with current employee of 20.

3. SUM OF ATTRITION BY GENDER : The male gender has the highest count of attrition of 150 while the female attrition count is 87.

4.SUM OF ATTRITION COUNT BY DEPARTMENT: The R&D Department has the highest attrition count of 133. Secondly, is the Sales Department with attrition count of 92 and the least is the HR Department with attrition count of 12.


### CONCLUSION
In summary, the attrition count is at a high rate in the Human Resources Educational field, Male Gender in the organization and the R&D Department.


