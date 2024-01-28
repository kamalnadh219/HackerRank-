# 002 - Revising the Select Query I

<br>

## Problem

Query all columns for all Americak cities in `CITY` with populations larger than `100000`. The `CountryCode` for America is `USA`.


## Input Format

The `CITY` table is described as follows :

![](https://s3.amazonaws.com/hr-challenge-images/8137/1449729804-f21d187d0f-CITY.jpg)

---

## Solution

```SQL

select * from city where countrycode ='USA'  and population >100000
```

<br>

**Output**

```
3878 Scottsdale USA Arizona 202705
3965 Corona USA California 124966
3973 Concord USA California 121780
3977 Cedar Rapids USA Iowa 120758 
3982 Coral Springs USA Florida 117549
```

