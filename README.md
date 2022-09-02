# Kyphosis-machine-learning

The first heatmap visualization shows that there are no missing values in the dataset.
In the second visualization, There are 64 values for the absence of kyphosis and 17 values for the presence of
kyphosis from overall data.Graph shows us that count for the kyphosis absent is more to that of the kyphosis
present.


In the pairplot, the graphs are plotted by taking attributes such as the Age, Number and Start with each other.
Kyphosis absence i.e blue is more in each graph than that of the kyphosis presence in each graph. The age
count is more for the absence of kyphosis means the age is more for kyphosis absent patients and the number
count for the absence is more as well.


The tree diagram shows the level 4 i.e depth=4 decision tree. The tree is first divided in 2 parts by taking the start
time. If the start is less than 8.5, it will be in the present class otherwise in the absent class. And this will go on
for each sample and we will get the result for that sample (like whether the kyphosis is present or not).
The feature importance graph of the decision tree classifier shows that decision tree also gives lot of importance
to the Start feature.And the decision tree completely ignored Age feature.And it chooses start as the most
informative feature overall. Moreover it gives importance to the Number feature as well.


The feature importance graph for the Random Forest Classifier gives more importance to the Start feature. Then
to the Age and then to the Number. Random Forest gives non-zero importances to many features than the
decision tree.


The feature importance graph of the Gradient Boosting Classifier finds Age as most important informative
feature. Then it considers Start as the important feature and after that it considers Number as the important
feature
