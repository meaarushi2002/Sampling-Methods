# Sampling
Implements Sampling on a given datset
# Sampling
Sampling is the process of selecting a subset of data from a larger dataset.
##
In this, we are applying five different sampling techniques on Credit card Fraud detection dataset.We will further analyze their accuracies and discuss the results.<br>
## Methodolgy
### 1. Converting Imbalanced dataset to balanced dataset: <br>
   In the given dataset, the class '1' has less number of samples. We solved this issue by oversampling class '1' instances
   and making them equal to class '0' instances.
   
### 2. Generating samples using five different sampling techniques: <br>
   1. Simple Random Sampling : A simple random sample is a subset of individuals chosen from a larger set in which a subset of individuals are chosen randomly, all with the same probability. We found the sample size using Sample size detection formula :

   2. Systematic Sampling : Systematic sampling is a probability sampling method where researchers select members of the population at a regular interval. We defined the step size by passing the arguments. 
      
   3. Stratified Sampling : Stratified sampling is a method of sampling from a population which can be partitioned into subpopulations. Here it is based on the class attribute. Then we select equal number of instances of both the subpopulations.
      
   4. Cluster Sampling : A probability sampling method in which you divide a population into clusters   and then randomly select some of these clusters as your sample.  
   5. Convenience Sampling :Convenience sampling is a non-probability sampling method where units are selected for inclusion in the sample because they are the easiest for the researcher to access.
### 3. Applying five ML Models on above five samples: <br>

   - Random Forest
   - Decision Tree
   - K-Nearest Neighbour
   - Logisitic Regression
   - SVM

### 4. Table : <br>
|               | Simple Random | Systematic | Cluster | Stratified | Convenience |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| Logistic Regression  | 0.938144 | 0.8 | 0.939815 | 0.915789 | 0.98 |
| SVM  | 0.670103 | 0.6 | 0.652778 | 0.652632 | 0.98 |
| KNN  | 0.886598 | 0.4 | 0.958333 | 0.863158 | 0.98 |
| Decision Tree | 0.927835 | 0.5 | 0.967593 | 0.926316 | 0.98 |
| Random Forest | 1.0 | 0.9 | 1.0 | 1.0 | 0.98
   
   
## Conclusion
 Random Forest Classifier is giving the best result in each sample.
