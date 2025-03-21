# This is the repository showcasing some of my work with SQL :)
My SQL is a work in progress!

### Query the list of CITY names from STATION that either do not start with vowels or do not end with vowels. Your result cannot contain duplicates.
This is a question from HackerRank which uses a version of SQL that doesn't accept 'AS' so you can't make aliases :( Also it only wants code on one line so you cant indent the code
```
SELECT DISTINCT CITY FROM STATION WHERE UPPER(SUBSTR(CITY, 1, 1)) NOT IN ('A', 'E', 'I', 'O', 'U') OR UPPER(SUBSTR(CITY, LENGTH(CITY), 1)) NOT IN ('A', 'E', 'I', 'O', 'U');
```
