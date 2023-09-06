# Association Rules
Association rules are a data mining technique used to find patterns in large datasets, revealing associations between items or events. 
These rules are often used in applications like market basket analysis, recommendation systems, and fraud detection. 
They consist of two key metrics: support (measuring itemset frequency) and confidence (measuring the strength of associations). 

For example, an association rule might be “Customers who order a pizza tend to add garlic bread to their order”. 

Algorithms like Apriori and FP-growth are commonly employed to discover these rules. Association rules help businesses optimize strategies, improve recommendations, and identify hidden relationships in their data.

## Implementation
- Importing the Libraries and Reading the dataset
- Pre-Processing the data
-  Applying the Apriori Algorithm
    - uisng different support and confidence values.
- Visualizations

## Packages Used
- Pandas
- Numpy
- Matplotlib.pyplot
- Seaborn
- Warnings
- from mlxtend.frequent_patterns import apriori,association_rules
- from mlxtend.preprocessing import TransactionEncoder
