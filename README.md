# sql-challenge
## Data Engineering and Analysis

### Applications used
* SQL
* Pandas
* SQLite
* ERD ( http://www.quickdatabasediagrams.com.)
* PostGres 11

### Activities Required
I created a SQL database that incorporated data from six different CSV files. To begin with, I had to analyze what was in each table and create an ERD to figure out how to fit the data together. From there, I was able to pull the SQL schema into PostGres to create the tables and run the queries. /


After creating tables and importing the CSV files, I was able to run several queries to be able to answer questions about human resource type information. Some of the information requested included:
* Employee Number, Name, Sex, and Salary
* Employee Name and Hire Date for employees hired in 1986
* Managers of each deprtment and personal information
* Name and sex for employees whose first name is "Hercules" and last name began with "B"
* People's names and information that worked in various departments
* Counts of how many employees shared the same last name/


There was also a bonus to import the database into Pandas to confirm that this data was falsified. Here I used three tables from the database, converted them into data frames, and used those to visualize the data. I created a histogram to show the most common salary ranges for employees. I then merged the data frames to select out the job titles and salaries related to those job titles to create a bar graph for the average salary by job title./

Finally, I searched my employee id number by using the loc function and found that my title was "April Fool's"
