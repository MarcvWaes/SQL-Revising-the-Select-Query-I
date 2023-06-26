# SQL-Revising-the-Select-Query-I

# Problem:
- Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.

- The CITY table is described as follows:

![vli1lpls zuo](https://github.com/MarcvWaes/practice-SQL---1/assets/120553175/240d70cc-0219-438f-9769-4aba84526991)

# Solution:
- SELECT *
- FROM CITY
- WHERE COUNTRYCODE = "USA" AND POPULATION > 100000

# Output:
- 3878 Scottsdale USA Arizona 202705
- 3965 Corona USA California 124966
- 3973 Concord USA California 121780
- 3977 Cedar Rapids USA Iowa 120758
- 3982 Coral Springs USA Florida 117549
