# Market_Basket_Analysis
  This project is dedicated to understanding the shopping habits of our local departmental store. This project aims to analyze the market buckets of a local departmental shop, providing valuable insights into our regular customers and their common purchases. By examining transaction data, we hope to uncover trends and preferences that can help the shop enhance customer experience and tailor its offerings. 
  Is a technique used by large retailers to uncover associations between items. It works by looking for combinations of items that occur together frequently in transactions, providing information to understand the purchase behavior. The outcome of this type of technique is, in simple terms, a set of rules that can be understood as “if this, then that”.
  We are going to use the Apriori algorithm to perform a Market Basket Analysis. The Apriori algorithm generates association rules for a given data set. An association rule implies that if an item A occurs, then item B also occurs with a certain probability. We are going to define four metrics to measure the precision of a rule
  1.  Support
Support is an indication of how frequently the item set appears in the data set. It’s the number of transactions with both X and Y divided by the total number of transactions.
  2. Confidence
For a rule X⇒Y, confidence shows the percentage in which Y is bought with X. It’s an indication of how often the rule has been found to be true.
  3. Lift
The lift of a rule is the ratio of the observed support to that expected if X and Y were independent.
  4. Conviction
It can be interpreted as the ratio of the expected frequency that X occurs without Y if X and Y were independent divided by the observed frequency of incorrect predictions.
     
