# Market-Basket-Analysis
Market Basket Analysis (MBA) is a data mining technique used to understand the purchase behavior of customers by finding associations between different items in large transaction datasets. The goal is to identify patterns or rules that indicate which products are frequently bought together. This information can be leveraged to optimize marketing strategies, product placement, inventory management, and cross-selling opportunities.

### Key Concepts in Market Basket Analysis:

1. **Itemset**: A collection of one or more items. For example, if a customer buys bread and milk, the itemset is {bread, milk}.

2. **Support**: The support of an itemset is the proportion of transactions in the dataset that contain that itemset. It indicates how frequently an itemset appears in the database. For example, if bread is bought in 30 out of 100 transactions, its support is 0.3.

3. **Confidence**: Confidence is a measure of the likelihood that a rule is true. For a rule like "If a customer buys bread, they also buy butter," confidence is calculated as the number of transactions containing both bread and butter divided by the number of transactions containing bread.

4. **Lift**: Lift is the ratio of the observed support to that expected if the two items were independent. A lift greater than 1 suggests that the two items are positively correlated; that is, the occurrence of one increases the likelihood of the other.

### Example:

Consider a grocery store's transaction data where customers frequently buy bread and butter together. By applying market basket analysis, the store might discover that:

- **Support**: 15% of all transactions include both bread and butter.
- **Confidence**: 70% of transactions that include bread also include butter.
- **Lift**: 1.2, indicating that bread and butter are bought together more often than by chance.

### Applications:

- **Retail**: Retailers can use MBA to determine which items to place near each other in stores or to create targeted promotions. For example, if diapers and baby wipes are frequently bought together, a retailer might place these items in close proximity.

- **E-commerce**: Online platforms use MBA for product recommendations ("Customers who bought this item also bought...").

- **Inventory Management**: By understanding which products are commonly bought together, businesses can optimize stock levels and reduce the chances of running out of popular items.

Market Basket Analysis is particularly valuable for businesses looking to maximize sales and improve customer satisfaction by offering more personalized shopping experiences.
