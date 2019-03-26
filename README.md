# 1340-project
1340 project stage 1

-Huang Hanting(3035534581)
-Zhong Yan(3035533989)

Idea 3: Cash register system

**Program Statement:** 

Shorten the grocery store waiting line for cashiers and maximize the profit.

**Program Setting:**

There is one line of customers with grocery waiting in line for the cashiers. The more the grocery one customer has, the time it takes to spend at the register will be longer. If the waiting time is longer than 15 minutes, the customers will leave without buying anything. Opening a new register costs an activation fee. 

**Program Feature:**
1. We will create a grocery file which includes grocery types, price and profit.
2. Read from grocery file: get input information: type of grocery and its profit, number of customers(at least 50 customers for testing).
3. For each customer the number of each product is randomly generated.
4. Calculate the processing time of one customer spent in the cashier, the time is proportional with the amount of grocery one customer has bought;
5. Calculate the profit each customer bring to the store.
6. Optimize the net profit by properly sequencing the customers. 
7. We will implement a new line if the porfit rest of the customers can bring is more than activation fee.
8. Optimize the number of cashier available due to the number of customers.
