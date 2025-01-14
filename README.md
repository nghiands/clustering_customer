**1. Introduction**

The goal of this project is to cluster customers based on age and gender, thereby analyzing shopping behavior and devising appropriate business strategies. The K-Means algorithm is used because of its efficiency and ability to group based on data characteristics
   
**2. Prerequisites**

- List of required libraries: `numpy`,`pandas`,`matplotlib`,`seaborn`,`sklearn`.
- You can install them in the following way:
```python
  pip install pandas numpy seaborn matplotlib scikit-learn
```
**3. Dataset**

This data set includes 9 columns:
- Transaction ID: transactions
- Date: date of purchase
- Customer ID: customer code
- Gender: gender
- Age
- Product Category: product types include: Beauty, Clothing, Electronics
- Quantity: quantity of goods purchased by customers
- Price per Unit: price per unit
- Total Amout: total amount
- Questions:

      - How does a customer's age and gender affect their purchasing behavior?
      - Which product category has the highest appeal to customers?
      - What is the relationship between age, spending, and product preferences?
      - How do customers adjust their shopping habits to seasonal trends?
  
You can also see the dataset details [here](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

**4. Expected Outcomes**

  ![image](https://github.com/user-attachments/assets/bb02bff5-353d-42e9-8b64-2ca63c93d099)

  ![image](https://github.com/user-attachments/assets/d1182af6-6604-41dd-a5a7-e884c7c3894e)

  ![image](https://github.com/user-attachments/assets/d3e4c62f-8872-4ad6-bc14-3b02d3f5b5ee)

  ![image](https://github.com/user-attachments/assets/7c788574-b123-4edf-95e7-8ff2e3810add)
  ![image](https://github.com/user-attachments/assets/8ee47103-0fcf-4643-9f64-c688ce041d14)



**5. Insights**
- The **main customer** group of the data set is customers from 36-60 years old, contributing 53% of total revenue, this is the most important customer group.
- **Female** customers are the main customers, contributing to 51% of revenue.
-	**Electronics**  is the sector that generates the **most revenue**, with great interest from male customers and the 36-60 age group
-	Shopping behavior:
    + *Summer and winter* have the *highest* number of transactions and revenues, especially in the Electronics sector.
    + **Female** customers prefer to shop at the **end of the year** (fall and winter), while **male** customers prefer to shop at the **beginning of the year** (spring and summer).
-	Spend analysis by age group:
    + The **36-60** age group  not only  spends the most, but also tends to shop in the middle of the week and contributes greatly to **Electronics sales**.
    + The **19-35** age group  is  more interested in the **fashion sector**, while the 61+ group  focuses on Electronics, and the 0-18 group  focuses on the beauty sector.
