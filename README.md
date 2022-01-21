## Machine Learning with Project
### Background introduction
The data set is obtained from the Wisconsin Breast Cancer Dataset from UCI Machine Learning Database. This dataset contains 699 fine needle aspiration biopsy sample units This dataset needs to be cleaned, processed, and modeled. The following are three aspects of machine learning: algorithm, model selection and evaluation.
### Method: 
**Conditional inference tree of algorithm of the conditional inference tree is as follows:**
(1) Calculate p-values for the relationship between the output variable and each predictor variable.
(2) Select the variable with the smallest p-value.
(3) Try all possible binary splits (by permutation tests) between the dependent variable and the selected variable, and select the most significant split.
(4) Divide the dataset into two groups and repeat the above steps for each subgroup.
(5) Repeat until all splits are insignificant or the minimum node has been reached.
This dataset has dependent or target variables: supervised learning models are considered. Including binary classification, multivariate classification and other algorithms. The classification algorithm belongs to supervised learning, which uses samples with known labels to establish a classification function or classification model, and applies the classification model. The performance function first extracts the correct number in the negative category (benign tissues are judged as benign), the number of misclassifications in the negative category (malignant tissues are judged as benign), and the number of misclasses in the positive category. These counts can be used to calculate sensitivity, characteristic, positive case hit rate, negative case hit rate and accuracy rate. At the same time, the function will display the normalized result.
### Results: 
Select a final best classifier. The performance of random forest mode is relatively better. However, the gap between each classifier is small, so the advantage of conditional inference tree may have a certain chance. Random forest successfully identified 96% of malignant samples and 98% of benign samples, and the overall prediction accuracy rate was as high as 97%.
