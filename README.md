# plsql-window-functions--MWUNGERI---Bonheur-

# DRINKS AND SNACKS ANALYSIS WITH WINDOW FUCYTIONS.
## problem definition.
A business of drinks (soft drinks and coffee) and snacks in Rwanda wants to analyze its sales data. Management needs to know the top products per region, customer spending patterns, and monthly growth.
## Succusses criteria
1. Top 5 products per region → rank()
2. Running monthly sales totals → sum() over()
3. Month-over-month growth → lag()
4. Customer quartiles → ntile(4)
5. 3-month moving averages → avg() over()

## Database schema
1. customers(customer_id, name, region)
2. products(product_id, name, category)
3. transactions(transaction_id, customer_id, product_id, sale_date, amount)
4. ER Diagram is provided in document below

## Queries and outputs
1. ranking top 5 products
2. aggregate
3. navigatio
4. distribution
   ### all above queris and results are included in document uploaded.

## Results analysis   
1.  Descriptive – What happened? (conducting reseach on top product, trending products).
2.  Diagnostic: Why it happened ( to get customer preferences, promotions).
3.  Prescriptive: What to do next (focus marketing on best-sellers, reward top spenders).

## References
i. W3schools

ii. https://youtu.be/9L0CMnDGuLg?si=vYwi3ZuA4RAF354t

iii. https://youtu.be/Ww71knvhQ-s?si=IzBr1nzBkQKXwhHr

iv. https://mode.com/sql-tutorial/sql-window-functions

v. https://drill.apache.org/docs/sql-window-functions-introduction/


 “All sources were properly cited. Implementations and analysis represent original work. No AI
generated content was copied without attribution or adaptation.”
