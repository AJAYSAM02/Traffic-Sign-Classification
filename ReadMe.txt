In this Python project example, we will build a deep neural network model that can classify traffic signs present in the image into different categories. With this model, we are able to read and understand traffic signs which are a very important task for all autonomous vehicles.
Steps to proceed with this project:-
1. Explore the dataset
- we have stored all the images and their labels into lists 
- With the sklearn package, we use the train_test_split() method to split training and testing data.
- From the keras.utils package, we use to_categorical method to convert the labels present in y_train and t_test into one-hot encoding.
2. Build a CNN model
- We compile the model with Adam optimizer which performs well and loss is “categorical_crossentropy” because we have multiple classes to categorise.
3. Train and validate the model
- After building the model architecture, we then train the model using model.fit().
4. Test the model with test dataset
- With matplotlib, we plot the graph to check for accuracy and efficiency

We built a graphical user interface for our traffic signs classifier with Tkinter. Tkinter is a GUI toolkit in the standard python library. Save it as gui.py.
To run it go to command prompt and go into the directory where the project is saved.
Run the command:- python gui.py
