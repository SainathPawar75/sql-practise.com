# sql-practise.com

This repository is dedicated to students and professionals who would like to brush up and advance their SQL skills for their careers. 
I found (https://www.sql-practice.com) educational and the web site user friendly however there wasn’t the complete solution book 
shared on the web site neither on GitHub.So now you can get the answers with alternative solutions for each question

I have used SQL Workbranch as main Database Management Systems (DBMS) and therefore you may encounter 
some queries that work in PostgreSQL may not work in other DBMS such as SQL Server or MySQL as some implementations slight vary in syntax.
For such cases, for example, in date and time operations I included standart SQL queries as well.


The test contains 50 questions and consists of 3 category:

Easy
Medium
Hard


You can use the following Entity Relationship Diagram (ERD)
to figure out what data to store, the entities, their attributes and also how entities relate to other entities.

![image](https://github.com/SainathPawar75/sql-practise.com/assets/139794162/c8ec20c7-615f-4d73-b3b0-184cb1b89e17)


[Section1: Easy]

Questions 1- 17

1. Show first name, last name, and gender of patients who's gender is 'M'

```
SELECT first_name,
       last_name,
       gender
FROM patients
WHERE gender = 'M';
```


