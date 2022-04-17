# All-state-purchase-prediction
The training and test sets contain transaction history for customers that ended up purchasing a policy. For each customer_ID, you are given their quote history. In the training set you have the entire quote history, the last row of which contains the coverage options they purchased. In the test set, you have only a partial history of the quotes and do not have the purchased coverage options. These are truncated to certain lengths to simulate making predictions with less history (higher uncertainty) or more history (lower uncertainty).

For each customer_ID in the test set, you must predict the seven coverage options they end up purchasing.

Solved the problem using Random Forest algorithm with the test accuracy of 0.89%
