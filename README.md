
# TRAFFIC SIGNS RECONATION

# ABSTRACT
The purpose of this project is to build a classification model that can categorize traffic signals in an image into several groups. We can read and understand traffic signs using CNN model.  I worked with a [GTSRB] dataset provided by Kaggle website. First, I started to explore the dataset, then I used Matplotlib and Seaborn tools to visualize the data .
after that I build Convolutional Neural Network model to predict the images from the test set.
#  DESIGN
we will build a convolutional neural network model that can classify traffic signs present in the image into different categories. With this model, we can read and understand traffic signs which are a very important task for all autonomous vehicles. CNNs are powerful neural networks that can easily extract features from images and help in object detection, face recognition and many other advanced vision applications.

![image](https://user-images.githubusercontent.com/94700188/146266028-19f54506-904b-4ea6-a8c7-b1032d8f8edb.png)

#  DATA
The dataset initially consisted of more than 50,000 images in total which has been divided into 43 classes. These classes represent the different types of traffic signs.
The dataset has two folders: a train folder that contains photos for each class and a test folder that will be used to evaluate our model.
#  ALGORITHMS
# Model
The implementation employs is Convolutional Neural Network with the following characteristics: 
Three Convolution Blocks, each with two, three, and three convolutional layers.
- Each Convolution Layer is followed by a BatchNormalization Layer.
- Each Convolution Block is followed by a Dropout Layer and a MaxPool Layer to prevent overfitting.
- Convolution Layers are followed by 3 Fully Connected Layers for categorization.
# Model Evaluation and Selection
we trained the model using model.fit after constructing the model architecture ().
We experimented with 32 and 64-batch sizes. When the batch size was set to 64 Our model performed better.
And the precision remained constant after 15 epochs.
# Test our model with test dataset
Our model got a 95% accuracy on the training dataset. With matplotlib, we plot the graph for accuracy and the loss.


# TOOLS
•	Numpy and Pandas for data manipulation
•	Scikit-learn for modeling
•	Matplotlib and Seaborn for plotting
•	Keras, Tkinter
# COMMUNICATION
plotting graphs for accuracy & loss
![image](https://user-images.githubusercontent.com/94700188/146266416-7f33030b-3244-41c6-b373-eb00ed38e0c3.png)
![image](https://user-images.githubusercontent.com/94700188/146267271-536c8fbf-67e4-4e0f-ab48-999979676243.png)



