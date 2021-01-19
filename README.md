# K Nearest Neighbors Model for Diabetes Dataset
Building, training, testing a K Nearest Neighbors model to predict diabetes occurrence from various factors  
Python, Jupyter Notebook, Anaconda, Scikit-Learn

## KNN algorithm
The K Nearest Neighbors model finds the proximity between a test point and nearby points. KNN is a lazy algorithm. This means it does not use the training data points to do any generalization. KNN is based on feature similarity - it figures out how closely out of sample features resemble our training set and classifies the given data point based on proximity to points in different clusters. Then, it predicts the outcome of the test points relative to which neighbors were closest.

## Training and testing data
A training dataset is a sample of data used to fit a model. The model sees and learns from the training dataset. The remaining data becomes the test dataset, which is used as an evaluation of the model that was fit on the training dataset.


## Data Processing
Steps I am taking to clean the data:
- First, I look at the distribution of each dataset visually (histograms for all columns)
- I will look to see whether data is normally distributed or skewed
- Replace 0's with NaN's where appropriate
- I replace NaN's with the mean for normal distributions. 
- I replace NaN's with the mode for skewed distributions. 
- This method is called imputing the data. Deletion is also an available tool for cleaning data.
