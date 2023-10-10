# Spambase database - Classification and Data Analysis

Main goal of our analysis is to create a classification rule that will help us deciding whether message should be classified as spam or non-spam based on frequency of appearance for certain words, numbers, characters or consecutive capital letters in phrases.

Firstly, we will firstly prepare the data:
1. gather information about attributes,
2. check types of all variables,
3. identify missing values,
4. analyze important metrics for every feature (mean, standard variance, quantiles and so on),
5. find which variables contribute mostly to being classified as either spam or non-spam,
6. detect and analyze outliers.

After that, we will use following classification algorithms:
1. linear discriminant analysis (LDA),
2. quadratic discriminant analysis (QDA),
3. logistic regression (LR),
4. K-nearest neighbours algorithm (KNN),
5. support vector machine (SVM).
  
We will try to optimize them by appropriately preparing or transforming data and optimize parameters of build-in python's functions in which following methods are already implemented. We will also try to ask ourselves, which metrics exactly we will try to maximize and what implications it will have on our classification.

# Requirements

1. Make sure that you are running Python 3.x
2. Install packages shown in the first cell of the .ipynb file. All of them can be downloaded using following formula:
```
pip install package_name
```
3. Run cells to see the results.

Alternatively, you can see results of the script without launching it by simply clicking it in the repository.
