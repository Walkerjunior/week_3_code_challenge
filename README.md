# week_3_code_challenge
## Write an SQL query to show the total payment amount for each payment date from payments table. (use sampleDB shared during week 2 class)😃

1. Display the payment date and the total amount paid on that date
```
                  SELECT SUM(amount) AS total_amount
                  FROM payments
                  WHERE paymentDate = '2004-12-17';
   ```
           
2. Sort the results by payment date in descending order.
   ```
                 SELECT amount, paymentDate
                 from payments
                 order by paymentDate
                 Desc;
   ```
5. Show only the top 5 latest payment dates.
   ```
                SELECT amount, paymentDate
                from payments
                order by paymentDate
                Desc
                Limit 5;
   ```
Happy coding 💻💻
