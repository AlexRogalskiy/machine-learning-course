
# [Session 1, January 7, 2020: Introduction to Machine Learning](./docs/introduction/README.md)

-----------

# [Session 2, January 9, 2020: Linear Regression](./docs/linear_regression/README.md)

----------

# [Session 3, January 14, 2020: Logistic Regression -- scikit](./docs/logistic_regression/README.md)

--------

# [Session 4, January 16, 2020: Logistic Regression -- scikit](./docs/logistic_regression/README.md)

* Logistic Regression
	* [Logistic Regression: Machine Learning Algorithm -- video ](https://www.youtube.com/watch?v=VCJdg7YBbAQ)
    * [Logistic Regression Details Pt1: Coefficients -- video](https://www.youtube.com/watch?v=vN5cNN2-HWE)
	* [Understanding Logistic Regression in Python](https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python)
	* [Logistic Regression using Python (scikit-learn)](https://towardsdatascience.com/logistic-regression-using-python-sklearn-numpy-mnist-handwriting-recognition-matplotlib-a6b31e2b166a)
	* [Building A Logistic Regression in Python, Step by Step](https://datascienceplus.com/building-a-logistic-regression-in-python-step-by-step/)
	* [Logistic Regression: A Concise Technical Overview](https://www.kdnuggets.com/2018/02/logistic-regression-concise-technical-overview.html)
	* [Understanding Logistic Regression step by step](https://towardsdatascience.com/understanding-logistic-regression-step-by-step-704a78be7e0a)
	* [Spark ML: Logistic Regression](https://medium.com/@dhiraj.p.rai/logistic-regression-in-spark-ml-8a95b5f5434c)

* Order of Lecture: 

1. [Watch a video: Logistic regression: 9 minutes](https://www.youtube.com/watch?v=yIYKR4sgzI8)

2. [INTRO_LOGISTIC_REGRESSION by Mahmoud Parsian](../../docs/logistic_regression/MP_INTRO_LOGISTIC_REGRESSION.txt.pdf)
  
3. [Watch a video: Logistic Regression: 19 minutes](https://www.youtube.com/watch?v=vN5cNN2-HWE&t=592s)
 
4. [LOGISTIC_REGRESSION slides -- 27](../../docs/logistic_regression/Logistic_Regression_slides_GOOD.pdf)
  
5. [Logistic Regression in Python: 53 minutes video -- watch at home](https://www.youtube.com/watch?v=VCJdg7YBbAQ)
      

-----------

# Session 5, January 21, 2020

* Students Project Presentation (LDA)

* What is TF-IDF?
	* term’s frequency (TF) and its inverse document frequency (IDF)

````
    TF-IDF  is an information retrieval technique 
    that weighs a term’s frequency (TF) and its 
    inverse document frequency (IDF). 
    
    Each word or term has its respective TF and IDF 
    score. The product of the TF and IDF scores of
    a term is called the TF-IDF weight of that term.
 
    Put simply, the higher the TF-IDF score (weight), 
    the rarer the term and vice versa.
````

* [TF-IDF, wiki](https://en.wikipedia.org/wiki/Tf–idf)

* [TF-IDF](http://www.tfidf.com)

* [What is TF-IDF?](https://monkeylearn.com/blog/what-is-tf-idf/)

* Logistic Regression Introduction

* [Spark ML: Logistic Regression](https://medium.com/@dhiraj.p.rai/logistic-regression-in-spark-ml-8a95b5f5434c)

<!--
spam/nospam: 
https://medium.com/@julsimon/building-a-spam-classifier-pyspark-mllib-vs-sagemaker-xgboost-1980158a900f
https://towardsdatascience.com/spam-detection-with-logistic-regression-23e3709e522
https://www.kaggle.com/abhikaggle8/pima-diabetes-classification/data
-->

* Introduction to K-means

----------

### Logistic Regression Examples:

1. [Python Logistic Regression with SciKit Learn](http://www.insightsbot.com/python-logistic-regression-with-scikit-learn/)

2. [Classification is Easy with SciKit’s Logistic Regression](https://sweetcode.io/easy-scikit-logistic-regression/)

3. [LOGISTIC REGRESSION EXAMPLE IN PYTHON (SOURCE CODE INCLUDED)](https://www.data-mania.com/blog/logistic-regression-example-in-python/)

4. [Logistic Regression 3-class Classifier -- Example 1](https://scikit-learn.org/stable/auto_examples/linear_model/plot_iris_logistic.html)

5. [Logistic Regression 3-class Classifier -- Example 2](https://ogrisel.github.io/scikit-learn.org/sklearn-tutorial/auto_examples/tutorial/plot_iris_logistic.html)

6. [Building A Logistic Regression in Python, Step by Step](https://datascienceplus.com/building-a-logistic-regression-in-python-step-by-step/)

7. [Logistic Regression in SciKit-Learn: Credit Card Data -- DISCUSS](https://www.kaggle.com/mgroncki/logistic-regression-in-scikit-learn)

8. [Logistic Regression using Python (scikit-learn): MNIST: digit recognition](https://towardsdatascience.com/logistic-regression-using-python-sklearn-numpy-mnist-handwriting-recognition-matplotlib-a6b31e2b166a)

9. [Logistic Regression with scikit-learn: good example with images](https://nbviewer.jupyter.org/gist/justmarkham/6d5c061ca5aee67c4316471f8c2ae976)

10. [Understanding Logistic Regression in Python](https://www.datacamp.com/community/tutorials/understanding-logistic-regression-python)

11. [Machine Learning — Using LogisticRegression with scikit-learn, Titanic data](https://medium.com/@kbrook10/day-10-machine-learning-using-logisticregression-with-scikit-learn-99316e6589cd)

12. [How to Make Predictions with scikit-learn by Jason Brownlee](https://machinelearningmastery.com/make-predictions-scikit-learn/)

-------

# Session 6, January 21, 2020
### Project Presentations

--------

# Session 7, January 23, 2020: K-means

### What is K-means clustering?

````
  K-means  clustering  is  a  method of  
  vector quantization,  originally from 
  signal processing, that is popular for 
  cluster analysis in data mining

  The algorithm always converges (by-definition) 
  but  not  necessarily  to  global  optimum.
````

### How does K-means work?

````
  The K-means algorithm starts by randomly 
  choosing a centroid value for each cluster. 
  After that the algorithm iteratively performs 
  three steps: 

  Given a set of data points (x1, x2,..., xn),
  K-means clustering aims to partition the n 
  data points into k (<=n) 
  sets S = {S1, S2, ..., Sk} 
  so as to minimize the within-cluster 
  sum of squares:
  
                k                    2
      arg min SUM  (SUM   || x -Mi ||   )
            i=1   X in Si

  Where Mi is the the mean of points in Si
````


### K-means Algorithm:

````
   The most commonly used algorithm is Standard 
   algorithm. Standard algorithm begins by assigning 
   k random points in the domain as the mean of each 
   cluster and then it iterates  the following  two 
   steps until it reaches the convergence:

   Step-1:   Find the Euclidean distance between 
             each data instance and centroids of 
             all the clusters; 

   Step-2:   Assign the data instances to the 
             cluster of the centroid with nearest 
             distance; 

   Step-3:   Calculate new centroid values based 
             on the mean values of the coordinates 
             of all the data instances from the 
             corresponding cluster.
````


### K-means Definition

* [Definition & Math Formula -- wiki](https://en.wikipedia.org/wiki/K-means_clustering)


### Example of Kmeans

1. [Example of Kmeans Algorithm:](mapreduce_algorithms_for_big_data_analysis_by_kyuseok_shim_KMEANS.pdf)

2. [K-means video: 9 minutes](https://www.youtube.com/watch?v=4b5d3muPQmA)

3. [K-Means Clustering with Scikit-Learn by Example](https://stackabuse.com/k-means-clustering-with-scikit-learn/)

4. [Introduction with image: Clustering using K-means algorithm](https://towardsdatascience.com/clustering-using-k-means-algorithm-81da00f156f6)

5. [K-means Clustering Algorithm: Explained](http://dni-institute.in/blogs/k-means-clustering-algorithm-explained/)

6. [K-means: Step-By-Step Example](http://mnemstudio.org/clustering-k-means-example-1.htm)

7. [Numerical Example of Kmeans clustering](https://people.revoledu.com/kardi/tutorial/kMean/NumericalExample.htm)

8. [Numerical Example of Kmeans clustering](https://www.saedsayad.com/clustering_kmeans.htm)

9. [Step by Step KMeans Explained in Detail](https://www.kaggle.com/shrutimechlearn/step-by-step-kmeans-explained-in-detail)

10. [Demonstration of k-means assumptions](https://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_assumptions.html#sphx-glr-auto-examples-cluster-plot-kmeans-assumptions-py)
	* plot_kmeans_assumptions.ipynb

11. [K-means Clustering: Iris data](https://scikit-learn.org/stable/auto_examples/cluster/plot_cluster_iris.html#sphx-glr-auto-examples-cluster-plot-cluster-iris-py)

12. [K-Means Clustering in Python -- detailed](https://mubaris.com/posts/kmeans-clustering/)


### K-means Spark

1. [Running KMeans clustering on Spark (CLASS Presentation: GOOD)](https://rsandstroem.github.io/sparkkmeans.html)

2. [UCLA Tutorial, K-means Clustering: GOOD WORKING EXAMPLE](http://web.cs.ucla.edu/~zhoudiyu/tutorial/)

3. [Clustering K-means](https://runawayhorse001.github.io/LearningApacheSpark/clustering.html)

4. [In Depth: k-means Clustering: excerpt from the Python Data Science Handbook - docs](https://jakevdp.github.io/PythonDataScienceHandbook/05.11-k-means.html)

5. [In Depth: M-means Clustering: excerpt from the Python Data Science Handbook - code](https://github.com/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.11-K-Means.ipynb)

--------


# Underfitting and Overfitting

* A model that generalizes well is a model 
  that is neither underfit nor overfit.

* Underfitting

````
    Underfitting occurs when a model can’t 
    accurately capture the dependencies among 
    data, usually as a consequence of its own 
    simplicity. It often yields a low 𝑅² with 
    known data and bad generalization capabilities 
    when applied with new data.
````

* Overfitting

````
    Overfitting  happens  when a  model learns  
    both dependencies  among  data  and random 
    fluctuations. In other words, a model learns 
    the existing data too well. Complex models, 
    which have many features or terms, are often 
    prone to overfitting.    When applied to known 
    data, such models usually yield high 𝑅². However, 
    they  often  don’t  generalize  well  and  have 
    significantly lower 𝑅² when used with new data.
````

* [What Are Overfitting and Underfitting in Machine Learning?](https://towardsdatascience.com/what-are-overfitting-and-underfitting-in-machine-learning-a96b30864690)

* [Overfitting and Underfitting in Machine Learning - video 17 minutes](https://www.youtube.com/watch?v=j9_yzC-x-js)


# Handling Non-Numeric Data:

* [Handling Categorical Data in Python](ttps://www.datacamp.com/community/tutorials/categorical-data)

* [Handling Non-Numeric Data (16 minutes video)](https://www.youtube.com/watch?v=8p6XaQSIFpY&feature=youtu.be)


--------

# Session 8, PCA

--------

# Session 9, LDA

-------

# Session 10: SVM

-------

# Session 11: Frequent Pattern Mining

-------