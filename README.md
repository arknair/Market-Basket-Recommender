# Market-Basket-Recommender
Utilizing association rule algorithms on customer transaction data to create a recommendation engine to predict the top 5 products a customer might potentially buy, given an input product.

We observe the creation of association rules using the following 3 algorithms:
1. Apriori
2. FP-Growth
3. HP-Mine

Once each algorithm is used to create association rules, the user can choose any specific product id and get recommendations on top products bought along with the user product, for each algorithm. The number of recommendations and product to recommend for, is chosen by the user.

This code can be utilized with other datasets which follow similar input format to create association rules. Additionally, in scenarios where considerable data is present for multiple levels like demography, country etc., these association rules can be created for specific groups and more pertinent results can be arrived at.
