# Handwritten_Digit_Recognition_Project

The handwritten digit recognition is the ability of computers to recognize human handwritten digits. In this project, I'm going to implement a handwritten digit recognition app using the MNIST dataset. I will be using a special type of deep neural network that is Convolutional Neural Networks. In the end, to build a GUI in which one can draw the digit and recognize it straight away.

[The MNIST dataset](http://yann.lecun.com/exdb/mnist/)

The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems.The database is also widely used for training and testing in the field of machine learning. It was created by "re-mixing" the samples from NIST's original datasets. The creators felt that since NIST's training dataset was taken from American Census Bureau employees, while the testing dataset was taken from American high school students, it was not well-suited for machine learning experiments. Furthermore, the black and white images from NIST were normalized to fit into a 28x28 pixel bounding box and anti-aliased, which introduced grayscale levels.

[Building Python Deep Learning Project on Handwritten Digit Recognition](https://github.com/sharonccs/Handwritten_Digit_Recognition_Project/blob/main/Handwritten_Digit_Recognition.ipynb)

Above is the notebook to implement the handwritten digit recognition project.

[Create GUI to predict digits](https://github.com/sharonccs/Handwritten_Digit_Recognition_Project/blob/main/GUI_Handwritten_Digit_Recognition.ipynb)

For the GUI, a new file is crreated to build an interactive window to draw digits on canvas and with a button to recognize the digit. The Tkinter library comes in the Python standard library. A function predict_digit() is created that takes the image as input and then uses the trained model to predict the digit.

Then the App class is created which is responsible for building the GUI for the app. A canvas is created where can draw by capturing the mouse event and with a button, it triggers the predict_digit() function and displays the results.

Screenshot
![GUI](https://github.com/sharonccs/Handwritten_Digit_Recognition_Project/blob/main/GUI.JPG)
