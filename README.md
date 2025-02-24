# Youtube-adview-Prediction
## Context :
Youtube advertisers pay content creators based on adviews and clicks for the goods and services being marketed. They want to estimate the adview based on other metrics like comments, likes etc. The problem statement is therefore to train various regression models and choose the best one to predict the number of adviews.

## Dataset:
The file train.csv contains metrics and other details of about 15000 youtube videos. The metrics include number of views, likes, dislikes, comments and apart from that published date, duration and category are also included. The train.csv file also contains the metric number of adviews which is our target variable for  prediction.

## Objective:
To build a machine learning regression to predict youtube adview count based on other youtube metrics.

## Steps and Tasks:
### 1. Import the datasets and libraries, check shape and datatype.

### 2. Visualise the dataset using plotting using heatmaps and plots. You can study data distributions for each attribute as well.

### 3. Clean the dataset by removing missing values and other things.

### 4. Transform attributes into numerical values and other necessary transformations.
Machine Learning models need data to be converted to numerical form at the end. We have categorical data and data in other formats which may want to convert. We will use label encoder and other date & time functions for that task.

### 5. Normalise your data and split the data into training, validation and test set in the appropriate ratio.
For a relatively small dataset like this, the training and test data split percentage should be high as 80:20. Normalisation is done to ensure all the features all weighted appropriately in the training stage. MinMax Scalar has been used which basically transforms each variable in the range of 0 to 1.

### 6. Use linear regression, support vector regressor, random forest and for training and get errors.
We will use the scikitlearn libraries for importing these models and the training them use the fit method and providing necessary labelled data (input and output). We are optimising for mean square error here because it's a regression problem after all. The metrics that we can use for us to compare different model can be mean square error and mean absolute error.

### 7. Use Decision Tree Regressor and Random Forest Regressors.
We need to give appropriate hyper parameters for them.

### 8. Build an artificial neural network and train it with different layers and hyperparameters.
we can play around with neural networks using the keras library which is quite similar to the scikit learn library.
Here we can define the model architecture (layers, number of neurons and activation functions), optimisation algorithm (like gradient descent or adam), cost function (mean square error) and give in the dataset.
We may need to perform hyperparameter tuning.

### 9. Pick the best model based on error as well as generalisation


