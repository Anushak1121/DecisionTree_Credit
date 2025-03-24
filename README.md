We are going to build a model that predicts if someone who seeks a loan might be a defaulter or a non-defaulter. We have several independent variables like, checking account balance, credit history, purpose, loan amount etc.

What does a bank want?
A bank wants to minimize the loss - it can face 2 types of losses here:
Whenever bank lends money to a customer, they don't return that.
A bank doesn't lend money to a customer thinking he will default but in reality he won't - oppurtunity loss.

Which loss is greater ?
Customer not returning the money back.
Since we don't want people to default on the loans we should use Recall as a metric of model evaluation instead of accuracy.

Recall - It gives the ratio of True positives to Actual positives, so high Recall implies low false negatives, i.e. low chances of predicting a defaulter as non defaulter
