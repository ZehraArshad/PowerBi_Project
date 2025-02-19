# Data Cleaning and Modelling

## Dataset 

We have a coffee sales dataset. It consits of a single large table

### Normalization

Since the data is de-normalized.

- Dividing data into transactions, stores and products table

### Data Cleaning
- Removed duplicates


### Data Modelling 
</br>

![image](https://github.com/user-attachments/assets/e1d4fa3b-d099-4be8-8783-681dddfa4424)

- Calculated measures like sales in transactions table by using unit prices and quantites. Transactions table  doesn't have unit price
- Utilized merge queries to merge datasets based on common column of product id between products and transactions
- Utilized parameters for sum of sales, average quantities to help in quicker analysis
- Applied core data analysis concepts like merge queries to bring sales from transactions to stores to find **sales made by each store**

  </br>
![image](https://github.com/user-attachments/assets/36d39ab8-7cb7-45a7-9ab8-bbb42fc277a9)

- Similarly applied group by to find products in each category.
</br>
  ![image](https://github.com/user-attachments/assets/9f75ebc6-2553-478a-90db-e133487465ba)
