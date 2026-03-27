## Name: Umesh Dhakal
## Course: MSCS634
## Professor: Dr. Satish Penmatsa
## March 27, 2026
## Lab 6 – Association Rule Mining with Apriori and FP-Growth

## Purpose of the Lab
- The goal of this lab was to practice frequent itemset mining and association rule mining using the Online Retail dataset.
- I cleaned the transaction data and converted it into a basket format so it could be used with Apriori and FP-Growth.
- I also created visualizations to better understand item frequency, item co-occurrence, and the discovered association rules.

## Key Insights and Observations
- Both Apriori and FP-Growth produced the same results. Both algorithms found 731 frequent itemsets and generated 842 association rules.
- FP-Growth was faster than Apriori. In my results, Apriori took about 0.4547 seconds, while FP-Growth took about 0.1114 seconds.
- This showed that FP-Growth was more efficient for this dataset because it uses a tree-based method and avoids generating too many candidate itemsets.
- The association rules showed meaningful relationships between items that were often purchased together.
- The visualizations helped show the most frequent items, item co-occurrence patterns, and the strength of rules using support, confidence, and lift.

## Challenges
- One challenge I faced in this lab was working with a large dataset that had many different items, which made the analysis more difficult.
- I also had to clean the data carefully by removing canceled invoices, missing values, and invalid rows before applying the mining algorithms.
