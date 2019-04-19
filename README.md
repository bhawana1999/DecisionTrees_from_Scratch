# DecisionTrees_from_Scratch


Decision tree is the most powerful and popular tool for classification and prediction. A Decision tree is a flowchart like tree structure, where each internal node denotes a test on an attribute, each branch represents an outcome of the test, and each leaf node (terminal node) holds a class label.

A tree can be “learned” by splitting the source set into subsets based on an attribute value test. This process is repeated on each derived subset in a recursive manner called recursive partitioning. The recursion is completed when the subset at a node all has the same value of the target variable, or when splitting no longer adds value to the predictions.

There are few key parameters to be noted while making a decision tree:-

1. GINI IMPURITY

Used by the CART (classification and regression tree) algorithm for classification trees, Gini impurity is a measure of how often a randomly chosen element from the set would be incorrectly labeled if it was randomly labeled according to the distribution of labels in the subset. The Gini impurity can be computed by summing the probability p i {\displaystyle p_{i}} p_{i} of an item with label i {\displaystyle i} i being chosen times the probability ∑ k ≠ i p k = 1 − p i {\displaystyle \sum _{k\neq i}p_{k}=1-p_{i}} {\displaystyle \sum _{k\neq i}p_{k}=1-p_{i}} of a mistake in categorizing that item. It reaches its minimum (zero) when all cases in the node fall into a single target category. 


2. INFORMATION GAIN

Information gain is used to decide which feature to split on at each step in building the tree. Simplicity is best, so we want to keep our tree small. To do so, at each step we should choose the split that results in the purest daughter nodes

![alt text](https://github.com/sona-19/DecisionTrees_from_Scratch/blob/master/Selection_003.png)



REFERENCES

https://www.youtube.com/watch?v=LDRbO9a6XPU

https://www.youtube.com/watch?v=QHOazyP-YlM

https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=12&cad=rja&uact=8&ved=2ahUKEwj1m66-qdzhAhUZb30KHY22AsAQFjALegQIABAB&url=https%3A%2F%2Fwww.geeksforgeeks.org%2Fdecision-tree%2F&usg=AOvVaw3qU9W7CoaWOcjv4VqiwoXG

