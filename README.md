# FLOWER-SPECIES-CLASSIFICATION



<img src="https://miro.medium.com/max/875/1*7bnLKsChXq94QjtAiRn40w.png">

This Project is thorugh application of machine learning with python programming.




# Project Description

- This dataset is a record of 3 common different iris species in Flower Family.

- Iris is a genus of around 300 species of flowering plants. It takes the name from the Greek goddess of rainbow, Iris.

- The Iris flower data set is also know as the Fisher's Iris data set. It is a multivariate data set introduced by Ronald Fisher in his paper, The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.

### Dataset information

- sepal length (in cm)
- sepal width (in cm)
- petal length (in cm)
- petal width (in cm)
class:
- Iris Setosa
- Iris Versicolour
- Iris Virginica

click here for downloading the datasets 

https://github.com/hariramgit/FLOWER-SPECIES-CLASSIFICATION/blob/master/iris_dataset.csv



## The main objective of the project is:

- The purpose was to compare different classification algorithms to predict the class of the iris flowers. Find and compare the accuracy of each model to find the best classifier. Finally train the model using the complete dataset.

- The final_model computed here can be used to predict the class of the iris flowers as Iris Setosa (or) Iris Versicolour (or) Iris Virginica given its attribute information namely the sepal length, sepal width, petal length and petal width values in centimeter.

- Classification models can be used to predict the dependent variable (class of each flower). Here we are going to use 4 different algorithms for classification namely, K-Nearest Neighbours, Decision Tree, Support Vector Machine and Linear Regression. Atlast we compare their accuracy to find the suitable classification technique for this problem. The given dataset is seperated into two seperate train and test sets. The train set is used to train the model, and the test set is used to predict the accuracy of each model. Finally, we compare the results.






## 📋 Tasks Performed
* 📂 EDA of the dataset
* 📂 cleaning the data 
* 📂 Feature Extraction
* 📂 Preprocessing
* 📂 constructing model
* 📂 Data Manipulation
* 📂 Data Visualizationx

### steps we did in this project
- importing the required models
- Uploading the datasets
- Cleaning and converting the data types
- Feature extractions
- Visualize pairplot and heatmap 
- preprossesing by lable encoding the datas
- Model selection and implementing the best model
- Moleding by using Naive Bayes Classification
- Moleding by using KNearestNeighbor
- Moleding by using  Descision tree classifier
- visualing the results







# RESULTS and OVERCOME:

It is always the best practice to train the model using the complete dataset i.e. not to waste any part of the available data. Thus, the complete dataset was modelled using Decision Tree Classifier. Let us visualize the tree:




## OUTPUT BRANCHES OF TREE:



[Text(0.3, 0.9166666666666666, 'X[3] <= 0.8\ngini = 0.665\nsamples = 105\nvalue = [34, 38, 33]'), 

 Text(0.2, 0.75, 'gini = 0.0\nsamples = 34\nvalue = [34, 0, 0]'),
 
 Text(0.4, 0.75, 'X[2] <= 4.75\ngini = 0.498\nsamples = 71\nvalue = [0, 38, 33]'),
 
 Text(0.3, 0.5833333333333334, 'gini = 0.0\nsamples = 34\nvalue = [0, 34, 0]'),
 
 Text(0.5, 0.5833333333333334, 'X[3] <= 1.75\ngini = 0.193\nsamples = 37\nvalue = [0, 4, 33]'),
 
 Text(0.2, 0.4166666666666667, 'X[2] <= 4.95\ngini = 0.5\nsamples = 6\nvalue = [0, 3, 3]'),
 
 Text(0.1, 0.25, 'gini = 0.0\nsamples = 2\nvalue = [0, 2, 0]'),
 
 Text(0.3, 0.25, 'X[3] <= 1.65\ngini = 0.375\nsamples = 4\nvalue = [0, 1, 3]'),
 
 Text(0.2, 0.08333333333333333, 'gini = 0.0\nsamples = 3\nvalue = [0, 0, 3]'),
 
 Text(0.4, 0.08333333333333333, 'gini = 0.0\nsamples = 1\nvalue = [0, 1, 0]'),
 
 Text(0.8, 0.4166666666666667, 'X[2] <= 4.85\ngini = 0.062\nsamples = 31\nvalue = [0, 1, 30]'),
 
 Text(0.7, 0.25, 'X[1] <= 3.1\ngini = 0.444\nsamples = 3\nvalue = [0, 1, 2]'),
 
 Text(0.6, 0.08333333333333333, 'gini = 0.0\nsamples = 2\nvalue = [0, 0, 2]'),
 
 Text(0.8, 0.08333333333333333, 'gini = 0.0\nsamples = 1\nvalue = [0, 1, 0]'),
 
 Text(0.9, 0.25, 'gini = 0.0\nsamples = 28\nvalue = [0, 0, 28]')]
 

## Visualize the TREE:

![Visualize the TREE](https://github.com/hariramgit/FLOWER-SPECIES-CLASSIFICATION/blob/dcee3ef1901bf812ba5273ca61b974de15886efb/iris_images/tree.png
)



## Length, Width of petals of all species

![Length, Width of petals of all species](https://github.com/hariramgit/FLOWER-SPECIES-CLASSIFICATION/blob/dcee3ef1901bf812ba5273ca61b974de15886efb/iris_images/lenght%20width%20of%20petals.png)

## Species Pairplot
![Species Pairplot](https://github.com/hariramgit/FLOWER-SPECIES-CLASSIFICATION/blob/dcee3ef1901bf812ba5273ca61b974de15886efb/iris_images/species%20%20pairplot.png)


## Heatmap
![Heatmap](https://github.com/hariramgit/FLOWER-SPECIES-CLASSIFICATION/blob/dcee3ef1901bf812ba5273ca61b974de15886efb/iris_images/heatmap%20iris.png)





## 🏗️ Built with
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)



## 👩‍💻 Libraries used
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=purple)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=yellow) 

![Matplotlib](https://img.shields.io/badge/Matplotlib-F7931E.svg?style=for-the-badge&logo=Matplotlib&logoColor=orange)
![seaborn](https://img.shields.io/badge/Seaborn-2C2D72?style=for-the-badge&logo=Seaborn&logoColor=blue) 

![ScikitLearn](https://img.shields.io/badge/ScikitLearn-F7931E.svg?style=for-the-badge&logo=ScikitLearn&logoColor=orange)





## Important models/algorithms were used in this project:
- GaussianNB
- LabelEncoder
- train_test_split
- KNeighborsClassifier
- Descision tree




## Organization
- Repository "(https://github.com/hariramgit/FLOWER-SPECIES-CLASSIFICATION/tree/master/code))": you may find the main Python Notebooks produced by me to realize the analysis, visualisations and predictive models.




## ✍️ Authors
*HARIRAM
* [Email](mailto:hariramhdmp@gmail.com)


## 🤝 Support
Contributions, issues, and feature requests are welcome!
Give a STAR if you like this project! and FOLLOW do SUPPORT Friends.
Thank you....

## 🤝 I hope you found the project useful and interesting. Feel free to contact me if you have any queries or suggestions...
