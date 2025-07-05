# DSA_Project-Power-BI-
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
A detailed power bi analytics project The Palmoria Group, a manufacturing company based in Nigeria,on gender-related issues within the organization and its
regions. Designed during my time at DSA Incubator, this project uses visualization tools for analysis which gives insights on the bordering on gender inequality in its 3 regions.

> 🪩 Objective: Analyse the company data and generate insights that the Palmoria management team would need to address
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🏢 Project overview
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The Palmoria Group, a manufacturing company based in Nigeria, is embroiled in issues bordering on gender inequality in its 3 regions. Unfortunately, the media recently published the news with the headline “Palmoria, the Manufacturing Patriarchy”. This doesn’t look good for the owners of the business, based on their ambition to scale the business to other regions and even overseas. I was hired as an HR Analytics expert to analyse the company’s HR data and come up with recommendations for management’s attention.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📰 Dataset Description
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Total Records: 945
- Columns: 6
- Source: Palmora's Company Database
- Each row represents: All Employee's Details
- Fields included:
  - Name
  - Gender
  - Salary
  - Locaton
  - Department
  - Rating
- Bonus Rule Table
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Additional Columns Added
  - Salary Band
  - Salary Sort
  - Dept_rating
  - Bonus Rule Value
  - Salary bonus
  - Total Bonus Salary
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🧠 Data Analytics
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
There were inconsistensies in the raw data. There were null values in the salary and department column
1. Data Cleaning: To improve the data integrity, the colums with null values were taken out
2. Formatting: The salary column was given the dollar currency
3. Power Query Analysis:
   - A conditional column (salary band, salary sort) was created
   - Department & rating columns joined together (Bonus Rule Table)
   - Merging tables:
     > Bonus rule table merged with employee data table
4.  calculations:
   - Salary Bonus
     - `[salary]*[bonus value]`
   - Total Salary Bonus
     - `[salary]+[salary bonus]`
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Solutions To Key Analytical Tasks
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Analyzed file
[palmora project](https://github.com/debbyadeshola1/DSA_Project-Power-BI-/blob/main/palmora%20project.pbix)

## Pointers 
1. Gender distribution in the organization
   - Visualization tool used : Donut Chart + filters for Location
2. Insights on ratings based on gender
   -  Visualization tool used : Stacked Column Chart
   -  Conclusion : Most Employee's had Average Ratings, The Male Employee's had higher ratings than the female employee's
3. Analyse the company’s salary structure
   - Visualization tool used : Custom column chart
   - Conclusion : There is a gender pay gap across the departments;

 ## Abuja
 - Product Management: Male highest Pay
 - Legal: Male highest Pay
 - Support: Male highest Pay
 - Sales: Female highest pay
 - Engineering: Female highest Pay
 - Accounting: Male highest Pay
 - Research & Development: Female highest Pay
 - Services: Female highest Pay
 - Marketing: Female highest Pay
 - Business Development: Female highest Pay
 - Training: Female highest Pay
 ## Kaduna 
 - Product Management: Male highest Pay
 - Legal: Male highest Pay
 - Support: Female highest Pay
 - Sales: Male highest pay
 - Engineering: Female highest Pay
 - Research & Development: Male highest Pay
 - Services: Male highest Pay
 - Marketing: Male highest Pay
 - Business Development: Female highest Pay
 - Training: Male highest Pay
 - Human Resources: Male highest Pay
## Lagos
 - Support: Male highest Pay
 - Sales: Male highest pay
 - Engineering: Male highest Pay
 - Accounting: Male highest Pay
 - Research & Development: Female highest Pay
 - Services: Female highest Pay
 - Marketing: Female highest Pay
 - Business Development: Male highest Pay
 - Training: Male highest Pay
   
