# Project_Algorithms_for_massive_datasets


The purpose of this project is to implement a scalable solution for finding frequent itemsets (in our
case pairs). In particular We implemented some of the algorithm seen in class, such as Apriori, PCY,
Multi-Hash, Multi-Stage and SON. All of them were applied to a sub-portion (We will discuss about
that) of the ”Ukraine Conflict Twitter” dataset given by the professor. The analysis performed is also
known as ‘market-basket analysis’ (or simply MBA).
What We did was preprocess the dataset and extract from it the baskets and the items that
compose them. In this context the basket are tweets and the items are the hashtags inside them. Then
starting from this set up, We started developing our solutions for the various algorithms cited before,
starting from Apriori and arriving to SON. At the end, We generated in a very simple way the various
association rules from our frequent pairs and calculated support, confidence, interest and lift for all of
them.

More about the work done in the Cavallari_Fiorio_MBApaper.pdf file in the repo.
