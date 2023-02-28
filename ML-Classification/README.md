# IBM Machine Learning Professional Certificate
## Supervised Machine Learning: Classification Course

This repository contains the various notebooks completed during the course Supervised Machine Learning: Classification for IBM's Machine Learning Professional Certificate on Coursera.

### 1.1-Logistic_Regression_Error_Metrics with Human Activity Recognition with Smartphones Dataset

Prepares dataset for classification. Label encodes target variable, performs EDA on the dataset and then performs a train test split of data. Logistic Regression is performed for classification with regularization. Also plots confusion matrix for each model.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 1.2-Logistic_Regression with Food Items Dataset

Applies Logistic Regression. Involves preprocessing and generating training and testing datasets, training and fine-tuning logistic regression models, interpreting trained logistic regression models and evaluating trained logistic regression models.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 2.1-KNN with Customer Churn Dataset

Makes use of K-Nearest Neighbor or KNN model. Involves EDA, Data Preparation and Encoding as well as Data Scaling and data splitting. The split data is used to evaluate different KNN models with varying values of K (nearest neighbors). The results are evaluated and the best value of K is selected.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 2.2-KNN with Tumor Dataset

Involves training KNN models with different neighbor hyper-parameters (values of K), evaluating KNN models on classification tasks, tuning the number of neighbors and finding the optimized one for a specific task.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 3.1-SVM with Wine Quality Dataset

Makes use of Support Vector Machine or SVM. Involves EDA of the dataset, creation of a binary target variable and Data Scaling. Subsequently,  Linear Support Vector Classifier (SVC) is discussed in detail. Then an SVC with a Gaussian kernel is used. Finally, kernel execution times for different kernels using Nystroem and Stochastic Gradient Descent Classifier are compared.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 3.2-SVM with Food Items Dataset

Involves training and evaluating SVM classifiers, tune important SVM hyperparameters such as regularization and kernel types and plot hyperplanes and margins from trained SVM models.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 4.1-Decision_Trees with Wine Quality Dataset

Applies decision tree classifier to dataset. Includes EDA, Stratified Shuffle Splitting of the data to maintain class balance in the target variable, and subsequently Decision Tree Classifiers are fit. Different depths of decision trees are used and the results evaluated for training and testing data. Depth is then used as a hyperparameter and optimized. The resulting decision tree is plotted.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, IO, Pydotplus*

### 4.2-Decision_Trees with Tumor Dataset

Involves training decision tree models with customized hyperparameters, evaluating decision tree models on classification tasks, visualizing decision tree models by plotting the tree and tuning the hyperparameters to find the optimized one for a specific task.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 5.1-Random_Forest with Customer Churn Dataset

Involves understanding the difference between Bagging and Random Forest Models, understanding that Random Forests have less Correlation between predictors in their ensemble, improving accuracy, how to apply Random Forest and understand yyperparameters selection for Random Forest models.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, Scipy*

### 5.2-Bagging with Customer Churn Dataset

Involves understanding what Bagging is, recognize that Random Forests is an implementation of bagging and its abilities, and describe the advantages of Random Forests over simply adding extra Decision Trees. Also discusses Extra Trees Classifier.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 5.3-Bagging 2

Involves understanding Bootstrap sampling, understanding Model Instability, applying Bagging and understanding when to use Bagging.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 5.4-Boosting_and_Stacking with Human Activity Recognition with Smartphones Dataset

Involves understanding how Gradient Boosting helps reduce error, identifying the benefits of using AdaBoost and interpreting the benefits of stacking models and comparing their results to boosted models.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 5.5-Ada_Boost with Customer Churn Dataset

Involves understanding that AdaBoost is a linear combination of 𝑇 weak classifiers, applying AdaBoost and understanding Hyperparameters selection in AdaBoost.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 5.6-Stacking_For_Classification with Wine Quality and Tumor Dataset

Involves understanding what Stacking is and how it works, understanding that Random Forests have less Correlation between predictors in their ensemble, improving accuracy, applying Stacking and understanding hyperparameters selection in Stacking.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn*

### 5.7-Gradient_Boosting with Customer Churn Dataset

Involves understanding Gradient Boosting is a linear combination of 𝑇 weak classifiers, applying Gradient Boosting using XGBoost and understanding Hyperparameters selection in XGBoost.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, Xgboost*

### 6.1-Model_Explanations

Discusses various model-agnostic explanation models. These include calculating Permutation Feature Importance, using Partial Dependency Plot to illustrate relationships between feature and outcomes, building Global Surrogate Models and building Local Surrogate Models using LIME.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, Lime*

### 6.2-Imbalanced_Data

Focuses on effective class weighting strategies that will assign minority class with more weights, so that it may have a larger impact on the model training process. Also discusses resampling methods that will generate synthetic datasets from the original datasets.
Involves identifying typical patterns of imbalanced data challenges, applying Class Re-weighting method to adjust the impacts of different classes in model training processes, applying Oversampling and Undersampling to generate synthetic datasets and rebalance classes and evaluate your consolidated classifiers using robust metrics such as F-score and AUC.

*Tools: Numpy, Pandas, Scikit-learn, Matplotlib, Seaborn, Imblearn, Collections*

### Classification Final Project Notebook

The final project makes use of the forest cover dataset provided by the UCI Machine Learning repository. The dataset includes various characteristics of forests as fatures. The dataset used for the project can be found at: [Dataset Link] (https://www.kaggle.com/datasets/uciml/forest-cover-type-dataset)
