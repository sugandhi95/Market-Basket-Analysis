# Market-Basket-Analysis
This PySpark project involves the implementation of the Apriori algorithm for frequent itemset mining and the subsequent generation of association rules.


A tab-delimited text file in which each row represents a basket of items is fed into the program. PySpark is then leveraged to mine n-frequent itemsets (where n = 2, 3, 4,...; 2-frequent itemsets are pairs, 3-frequent itemsets are triples, etc.) , as determined by a threshold (a.k.a the support), using the Apriori algorithm. These itemsets are then used to generate association rules based on a predefined threshold (a.k.a the confidence). The association rules are then saved to a local folder.
