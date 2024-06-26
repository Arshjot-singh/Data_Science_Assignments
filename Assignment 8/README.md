  # Assignment 8- Parameter Optimization in SVM
## UCS654: Predictive Analytics using Statistics


### Support Vector Machine
In machine learning, support vector machines or SVMs are supervised learning models with associated learning algorithms that analyze data for classification and regression analysis. It is used to find a hyperplane that best separates the two classes, or the plane that has the maximum distance from both the classes. SVM works best with smaller datasets.

### Parameter Optimization
Optimization of parameter values means finding the best combination of the parameters that governs the model, to enable it to perform the given task with relative accuracy.
The hyperparameters tuned in the SVM model were:- 
| Parameters | Description  |
|-----------------------|--------|
| kernel | the type of kernel used for the SVM    |
| c (epsilon) | penalty parameter of the error term  |
| degree (nu) | the degree of the polynomial kernel     |


### About Dataset used
The dataset used for the project is [Room Occupancy Estimation](https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation#) that has been downloaded from the UCI Machine Learning Repository. 
- Number of Instances: 10129
- Number of Attributes: 16

### Data Analytics and Parameter Optimization steps 
    1. Data Cleaning
    2. Data Preprocessing
    3. Normalization
    4. Creating 10 samples with 70-30 ratio of Training and Testing Set
    5. Optimizing the SVM model for each sample, by using grid search and cross-validation with 1000 iterations.


### Final Result Table
![Result](https://github.com/Arshjot-singh/Data_Science_Assignments/assets/107791587/19d04956-b564-400f-8997-5732f4324d21)

### Convergence Graph
![Convergence Graph](https://github.com/Arshjot-singh/Data_Science_Assignments/assets/107791587/7f424d8e-458d-4cab-bc01-448f236465f1)

### Conclusion
From the table, it can be concluded that ***Sample 8*** shows the ***best accuracy of 0.97***, and hence the most optimized parameters being ***kernel= poly , Nu= 8.90, epsilon= 3.76***. 
From the convergence graph, it can be concluded that the objective function decreases and increases rapidly in the earlier iterations. In the later iterations, the function seems to be converging, and will ultimately lead to a stable solution after further more iterations.
