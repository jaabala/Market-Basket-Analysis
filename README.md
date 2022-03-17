# Market-Basket-Analysis
# 1. Defining the Question

# a) Specifying the Data Analysis Question
Identify the top 10 products likely to be purchased together and maximise revenue.

# b) Defining the Metric for Success
This project will be considered a success when:
1. we are able to confidently determine which products are likely to be purchased together identify fequent itemsets

# c) Understanding the Context
Care five is a German multinational retail corporation headquartered in Berlin, Germany. It is the eighth-largest retailer in the world by revenue. It operates a chain of hypermarkets, groceries stores, and convenience stores, which as of January 2021, comprises its 12,00 stores in over 30 countries.

As a Data analyst working for one of the stores, you must perform market basket analysis to help the store maximize revenue. More specifically, your task will analyze transactional data to identify the top 10 products likely to be purchased together.

# d) Recording the Experimental Design
1. Define the business question
2. Perform data importation and loading
3. Perform data preprocessing
4. Find frequent itemsets
5. Generate association rules
6. Perform metric interpretation and provide recommendation

# e) Data Relevance
The data provided is sufficient and appropriate for answering the research question.

# 2. Summary of Findings
Toothpaste, pencils and candybars with a lift of 2.75 indicaitng a strong association. The lift value of 2.75 means that (Toothpaste & pencil) purchase lifts the Candy bars purchase by 2.75 times.

The output above shows the Top 10 itemsets sorted by confidence value and all itemsets have support value over 1% and lift value over 2 majorly.

# 3. Recommendations
We can conclude that there is indeed evidence to suggest that the purchase of most items leads to the purchase of Candy bars, greeting cars & magazines. Care Five should consider bundling toothpastes,greeting cards, magazines and candy bars together as a set, the staff in the store should also be trained to cross-sell these items to customers who purchase toothpaste, pencils, greeting cards or magazines knowing that they are more likely to purchase them together, thereby increasing the store's revenue.

# 4. Challenging your Solution
a) Did we have the right question?
Yes

b) Did we have the right data?
Yes, the data was sufficient to determine top selling products and item sets.

c) What can be done to improve the solution?
We can incorporate transactions with more than one product types sold to further understand the associations
