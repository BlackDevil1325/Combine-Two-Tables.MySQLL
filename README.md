# Combine-Two-Tables.MySQLL





SELECT 
    P.firstName AS FirstName, 
    P.lastName AS LastName,    
    A.city AS City,         
    A.state AS State         
FROM 
      Address A            
RIGHT JOIN 
    Person P
ON 
    A.personid = P.personid; 
