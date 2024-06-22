# SQL-email-employee-generator-
SQL email employee generator  

SELECT CONCAT (LOWER (firstname),'.', LOWER (lastname),'@company.com') AS email

FROM Employees 

ORDER BY firstname ASC 
