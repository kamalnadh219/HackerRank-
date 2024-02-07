
# Type of Triangle


## **MS SQL** solution

```sql
select case when A+B>C and B+C>A and  A+C>B then 
case when A=B and B=C then 'Equilateral' 
     when A=B or B=C or C=A then 'Isosceles'
     else 'Scalene'
end
else "Not A Triangle"
end
from  TRIANGLES
```
