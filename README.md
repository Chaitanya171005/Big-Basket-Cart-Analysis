Overview

This project performs Market Basket Analysis on a BigBasket dataset containing around 7500 transaction rows.
The main objective is to identify which products are frequently purchased together using the Apriori Algorithm and Association Rule Mining.

The project helps understand customer purchasing behavior and can be useful for:

Product recommendation systems

Cross-selling strategies

Store layout optimization

Personalized marketing

Bundle creation

Problem Statement

E-commerce platforms like BigBasket generate huge amounts of transactional data daily.
Analyzing customer purchase combinations helps businesses discover hidden buying patterns.

This project answers questions like:

Which items are commonly bought together?
What products increase the likelihood of purchasing another product?

Which product combinations have strong association rules?

Dataset

The dataset contains:

Approximately 7500 rows of transactions
Multiple grocery products purchased in each transaction

Technologies Used

*Python

*Pandas

*NumPy

*Matplotlib

*Seaborn

*Jupyter Notebook

Algorithm Used

*Apriori Algorithm

The Apriori algorithm is used to find:

Frequent itemsets

Association rules between products

The algorithm works on:

*Support

*Confidence

*Lift

Important Metrics

Support

Measures how frequently an itemset appears in the dataset.
​	
 
Confidence
Measures the probability of purchasing item B when item A is purchased.
​
Lift

Measures how strongly two products are associated.
 
Project Workflow

1. Data Collection
Imported BigBasket transactional dataset.
2. Data Preprocessing
Removed null values
Converted transactions into list format
Applied one-hot encoding
3. Frequent Itemset Generation
Used Apriori algorithm to generate frequent product combinations.
4. Association Rule Mining
Generated rules using:
Minimum support,
Minimum confidence,
Lift threshold

Conclusion
This project demonstrates how Apriori-based Market Basket Analysis can extract valuable purchasing patterns from BigBasket transactional data.
The generated association rules help businesses improve recommendation systems, marketing strategies, and customer experience.
