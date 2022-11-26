# LSEG-task5
Database with sql commands

Task 5:
1) SELECT * FROM CUSTOMERS JOIN ORDERS on CUSTOMERS.ID=ORDERS.CustomerID;\
Or SELECT * FROM CUSTOMERS INNER JOIN ORDERS on CUSTOMERS.ID=ORDERS.CustomerID;\
2)UPDATE CUSTOMERS SET Type = 'Corn' WHERE CUSTOMERS.ID = 2;\
3)SELECT sum(CountryAmount) as Summary_Country_Amount FROM CUSTOMERS WHERE CUSTOMERS.Country = 'UK';\\
SQL files have been attached in repo
