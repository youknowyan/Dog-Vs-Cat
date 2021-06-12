This is the final individual project of Udacity Nanodegree: Machine Learning Engineer(Advanced). The name of this project is “Cat Vs dog” and its goal is to use deep learning (Convolutional Neural Network) to build and optimize a prediction model which can identify if a photo is about dogs or cats.

The files included are preprocessing.ipynb | pred.ipynb | result.csv | README. pdf | preprocessing.html | pred.html

The actual project files are “ preprocessing.ipynb”and “ pred.ipynb”. “result.csv” is my final predict outcome of testing set.“ preprocessing.html”and“ pred.html” are HTML version of ipynb file which are easier for you to read.

This project requires Keras，TensorFlow，Python 3，Jupyter notebook. 

The functions used in this project are keras.models，keras.layers，keras.applications，keras.preprocessing.image，sklearn.utils，h5py，numpy，pandas，matplotlib.pyplot，pillow，scikit-learn，os，shutil

This project was designed to run on tensorflow_p36 of AWS AMI（deep learning ubuntu），and scikit-learn & pillow need to be installed as well.


Please follow the steps below if you would like to run this project:

1.Download dataset from Udacity Github to your AWS Instance. Ensure to extract train.zip, test.zip and sample_submission.csv to the same directory. Then copy preprocessing.ipynb and pred.ipynb to the same directory.

2.Run preprocessing.ipynb to preprocess data and transfer info of training photos into feature vectors which will generate a new file “ model_test.h5”（This will take approximately 10-15 mins under AWS p3.2xlarge）

3.Run pred.ipynb to predict the test set and generate predict outcome result.csv，then you can upload result.csv to Kaggle to see its rank(This will take approximately 30s）
