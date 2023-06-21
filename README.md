Neural Networks:
Neural networks are powerful models inspired by the structure and function of the human brain. They consist of interconnected nodes (neurons) organized in layers. Here's an example of training a simple neural network using the Keras library:

Explanation:

We import the necessary modules from TensorFlow and Keras.
We create a sequential model using keras.Sequential().
Layers are added to the model using model.add(). In this example, we add three dense layers, where the first two layers have ReLU activation and the last layer has softmax activation for multi-class classification.
The model is compiled with an optimizer, loss function, and metrics using model.compile(). In this case, we use the Adam optimizer and categorical cross-entropy loss.
The model is trained on the training data using model.fit(), specifying the batch size, number of epochs, and optional validation data.
Finally, we evaluate the model on the test data using model.evaluate() and obtain the test loss and accuracy.
