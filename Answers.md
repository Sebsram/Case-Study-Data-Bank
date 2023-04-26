# Customer Nodes Exploration
**1. How many unique nodes are there on the Data Bank system?**

![a1](https://user-images.githubusercontent.com/130475600/234620597-96390560-1b18-4ff0-998a-1b71038b9a3d.PNG)

| count |
| ----- |
| 5     |

**2. What is the number of nodes per region?**

![a2](https://user-images.githubusercontent.com/130475600/234621998-0740405c-36d1-4235-8282-58ed78b02c42.PNG)

| region_name | total_count |
| ----------- | ----------- |
| America     | 735         |
| Australia   | 770         |
| Africa      | 714         |
| Asia        | 665         |
| Europe      | 616         |

**3. How many customers are allocated to each region?**

![a3](https://user-images.githubusercontent.com/130475600/234622878-68f00309-2585-424c-ab5c-8b34adfd71c9.PNG)

| region_id | total_costumers |
| --------- | --------------- |
| 1         | 770             |
| 2         | 735             |
| 3         | 714             |
| 4         | 665             |
| 5         | 616             |

**4. How many days on average are customers reallocated to a different node?**
![a4](https://user-images.githubusercontent.com/130475600/234628028-6a707849-85d4-491e-b690-7252ebbab0e7.PNG)

| average_days |
| ------------ |
| 23.6         |

# Customer Transactions

**1. What is the unique count and total amount for each transaction type?**

![ct1](https://user-images.githubusercontent.com/130475600/234629511-270057c3-57c2-457c-b9e5-b2dd1c68da3e.PNG)

| txn_type   | count | total_amount |
| ---------- | ----- | ------------ |
| deposit    | 2671  | 1359168      |
| purchase   | 1617  | 806537       |
| withdrawal | 1580  | 793003       |

**2. What is the average total historical deposit counts and amounts for all customers?**

![ct2](https://user-images.githubusercontent.com/130475600/234633021-2170b5ea-57ad-42d4-8cfb-162c5c589f64.PNG)

| avg_deposit | avg_amount |
| ----------- | ---------- |
| 5           | 508.61     |

**3. For each month - how many Data Bank customers make more than 1 deposit and either 1 purchase or 1 withdrawal in a single month?**

![ct3](https://user-images.githubusercontent.com/130475600/234637601-e3750d1c-6771-4aa4-a651-651d75e4929a.PNG)

| month | c_count |
| ----- | ------- |
| 1     | 158     |
| 2     | 240     |
| 3     | 263     |
| 4     | 86      |

**4. What is the closing balance for each customer at the end of the month?**
a
