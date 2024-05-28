# Network-Analysis-of-product-co-purchasing-in-Amazon
Customers Who Bought This Item Also Bought" feature of the Amazon website, based on data collected in March 2003 is considered for the Network analysis.

**Dataset Description**

The amazon co-purchasing dataset has 2 variables namely :
1.	FromNodeId : Product i purchased (source node in the network)
2.	ToNodeId : Product j co- purchased with product i (target node in the network)

This dataset is not just a representation of consumer purchasing patterns at the time, but also a complex network structure illustrating the intricate relationships and dynamics within Amazon's vast product ecosystem. The analysis of such a network can provide valuable insights into consumer behavior, product affinity, and can inform strategies for product placement, recommendation systems, and marketing.

**Analysis**

1) There are 564 unique products in the dataset and there are 1164 instances where one product was frequently co-purchased with another. 
2) On average, each product is co-purchased with about 4 other products.
3) The most frequently bought product is product 8 with a frequency of 29 and the least frequently bought product is 418 with a frequency of 1.

**Node Importance**

In the context of the Amazon co-purchase network dataset, various node importance techniques can be employed to determine the most central or influential products.

**Degree Centrality:** Assesses importance based on the number of connections a node has. Higher degree centrality indicates a product is frequently co-purchased with many other products. Product ID 8 has the highest degree of centrality and is most co-purchased.

**Betweenness Centrality:** Identifies products that serve as bridges between different parts of the network. A high betweenness centrality score suggests a product plays a crucial role in connecting otherwise unrelated products. Product ID 8 followed by 20, 30 have high betweenness centrality score.

**Closeness Centrality:** Calculates how close a product is to all other products in the network. Products with high closeness centrality can quickly influence or be influenced by others. Product ID 8 followed by 20, 7 have high closeness centrality scores.

**Eigenvector centrality:** considers not just the number of connections, but also the quality, identifying products co-purchased with other well-connected products. Product ID 197, 230, 227, 231, 229 are connected to well-connected products.

**Community detection analysis from the plot**

•	From the network, we can conclude that a total of 27 communities were identified. This suggests that the network has a modular structure, with certain groups of nodes (i.e., products) being more interconnected with each other than with products in other communities. For example, product 8 is largely clustered, indicates it’s likely to be co-purchased, followed by 20 and 30. 
•	The communities vary in size, with some consisting of many nodes and others with fewer. This could reflect different product categories, with larger communities possibly representing more popular or general product categories and smaller ones indicating niche market products.
•	Inter community links are also observed which indicate that these products that serve as connectors or 'gateway' items are co-purchased with products from different categories.

**Conclusion**

Based on the dataset and the graph visualization provided, we can conclude that the Amazon co-purchase network exhibits a rich and complex community structure, indicative of diverse consumer purchasing patterns. The density and interconnectivity at the network's core represents popular or versatile products that act as hubs, commonly co-purchased with many other items across various categories. The presence of smaller, distinct communities at the periphery suggests niche markets or specialized products with a more focused customer base. 
