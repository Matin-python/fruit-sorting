# 🍎 Fruit Classification using Machine Learning

A Machine Learning project that classifies different types of fruit using four classification algorithms: Logistic Regression, Decision Tree, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM).


## Overview

This project uses a fruit dataset containing numerical measurements of different fruits. The features include mass, width, height, and color score.

The dataset is processed and divided into training and testing sets. Feature scaling is performed using `MinMaxScaler`, and four different Machine Learning classification algorithms are trained and evaluated using both training and test accuracy.

The project also includes a scatter matrix visualization to explore the relationships between the input features.


## Features

* Fruit classification
* Data preparation and feature selection
* Scatter matrix visualization
* Feature scaling using Min-Max normalization
* Logistic Regression classification
* Decision Tree classification
* K-Nearest Neighbors classification
* Support Vector Machine classification
* Training and test accuracy evaluation


## Technologies Used

* Python
* Pandas
* Matplotlib
* Scikit-learn


## Dataset

The project uses the following dataset:

```text
fruit.txt
```

The dataset contains information about different types of fruit.

The following features are used for classification:

```text
mass
width
height
color_score
```

The target variable is:

```text
fruit_label
```

which represents the fruit class.

The columns `fruit_name` and `fruit_subtype` are removed before training because they are not used as input features.


## License

This project is licensed under the **MIT License**.


## Author

**Mohammad Reza Bakhshandeh**

Electrical Engineering (Electronics) Graduate

Interested in Python Development, Computer Vision, Machine Learning, and Artificial Intelligence.
