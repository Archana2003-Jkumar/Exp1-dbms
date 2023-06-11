# Exp1-dbms
## AIM:
To fetch first name from the worker table using alias from the sample data using SQL query.
## ALGORITHM:
1.Create a table named "worker" with required columns.
2.Insert the sample data into the "worker" table.
3.Fetch the first names by executing the SQL query: "SELECT name AS FIRST_NAME FROM worker;".
4.Retrieve the result set containing the first names from the query execution.
5.Display or process the retrieved first names as needed.
## PROGRAM:
```
DEVELOPED BY:RITHIGA SRI.B
REGISTRATION NUMER:212221230083
CREATE TABLE worker (
    id INT,
    name VARCHAR(50),
    age INT,
    salary DECIMAL(10, 2)
);
INSERT INTO worker (id, name, age, salary)
VALUES
    (1, 'John', 30, 5000.00),
    (2, 'Jane', 25, 4500.00),
    (3, 'Mike', 35, 6000.00),
    (4, 'Sarah', 28, 5500.00),
    (5, 'David', 32, 5200.00);
SELECT name AS FIRST_NAME
FROM worker;
```
## OUTPUT:
![image](https://github.com/Archana2003-Jkumar/Exp1-dbms/assets/93427594/4ddb78fd-b793-423e-8570-689156c79ce5)

## RESULT:
Thus, a sql query to fetch first name from worker table using alias from sample data is executed successfully.


