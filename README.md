
# Hackerrank 

I'm gonna answer some of hackerrank mysql questions

### section 1

#### Q1:
Query all columns for all American cities in the CITY table with populations larger than 100000. The CountryCode for America is USA.
```mysql
SELECT * FROM CITY WHERE COUNTRYCODE = 'USA' && POPULATION > 100000;
```

![section 1 first answer](section_1/section1_1.png)

#### Q2:
Query the NAME field for all American cities in the CITY table with populations larger than 120000. The CountryCode for America is USA.
```mysql
SELECT C.NAME FROM CITY C WHERE C.COUNTRYCODE = 'USA' AND C.POPULATION > 120000;
```

![section 1 second answer](section_1/section1_2.png)
