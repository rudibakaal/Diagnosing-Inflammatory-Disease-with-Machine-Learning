# Diagnosing-Inflammatory-Disease-with-Machine-Learning

## Motivation
A multivariate binary classification algorithm for diagnosing the presence of cystitis based on medical data. 

The data was created by a medical expert as a data set to test the expert system, which will perform the presumptive diagnosis of two diseases of the urinary system.[1].

On account of the multivariate nature of the data set[2], one hot encoding of the categorical features was implemented with pandas cat.codes class. All features were also standardised via sklearn's StandardScaler class.

## Neural Network Topology and Results Summary

The binary-crossentropy loss function was leveraged along with the Adam optimizer for this classification problem.


![model](https://user-images.githubusercontent.com/48378196/96961401-4be81500-1550-11eb-9cd2-4e0f682c3b56.png)

After about 70 epochs the binary classifier reaches 100% accuracy in the cystitis diagnosis. 

![cystitis classification](https://user-images.githubusercontent.com/48378196/96993734-70a3b300-1577-11eb-9c6c-b43ff5362563.png)

Although impressive, considering the relatively small data set of 120 instances, these expectations should be judiciously adjusted when applied to larger data sets.


## License
[MIT](https://choosealicense.com/licenses/mit/) 

## References
[1] J.Czerniak, H.Zarzycki, Application of rough sets in the presumptive diagnosis of urinary system diseases,
Artifical Inteligence and Security in Computing Systems, ACS'2002 9th International Conference Proceedings,
Kluwer Academic Publishers,2003, pp. 41-51
[2] https://archive.ics.uci.edu/ml/datasets/Acute+Inflammations
 
