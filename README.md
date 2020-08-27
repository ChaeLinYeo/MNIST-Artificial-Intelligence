# MNIST-Artificial-Intelligence
Artificial intelligence projects using the MNIST dataset and Python, Scikit-learn, and TensorFlow.<br>
* Perceptron, Logistic Regression, SVM 분류기를 이용하여 최상의 MNIST학습 결과 도출하기<br>
* SVM Classifier + Stochastic Gradient Descen 으로 MNIST의 Multi-Label Classification Problem 해결하기<br>
* Standard Scaling, PCA, Convolution, Polynomial 전처리작업 및 작업물을 그래프로 도식화시키기<br>
<br>
### PBL01
The given PBL Case is making a system to read the serial numbers of the car parts produced in their factory.<br>
Namely, It is creating an accurate digit classification system.<br>
And then, our object is finding the best model out of the given classifiers and hyperparameters.<br>
The classifiers are Logistic Regression and Support Vector Machine, and a data is MNIST as we saw in class, and a criterion is F1-score, which is the harmonic mean of precision and recall.<br>
The problem of our project is to find out which Machine Learning model would be best to classify this MNIST.<br>
<br>

### PBL02
Using an SVM classifier, implement a maximized margin aolong with the data can be classified. <br>
Stochastic Gradient Descent would then be used along with Mini-Batches to update the weights in order to create a solution for the multi-label classification prolbem at hand.<br>
To conclude,
Data scaling proved incredibly important, having increased the accuracy in every case where we implemented it.<br>
PCA also allowed our algorithms to run in a much shorter time however retained accuracy all the while.<br>
However, ran on its own PCA without scaling is not recommendable since normalization is needed prior to PCA.<br>
GridSearch although time consuming proved incredibly important in the grand scheme of hyperparameter tuning.<br>
<br>

### PBL03
The training data consisted of a total of 80,000 data points including the D1, D2 and the new1k data set. Of the 80,000 data, 30% of it was separated and used as the test set.<br>
We set our hyperparameters; C, learning rate and batch size to the following values.<br>
Convolution, PCA and Polynomial were used to preprocess the data.<br>
<br>
