🧮 MNIST Digit Classifier (PyTorch + Google Colab)

This project is a handwritten digit classifier built using the MNIST dataset and PyTorch.
The model is trained in Google Colab to recognize digits (0–9) from grayscale images.

🚀 Features

Loads and preprocesses the MNIST dataset (60,000 training + 10,000 testing images).

Implements a neural network using PyTorch.

Trains and evaluates the model on test data.

Computes overall accuracy.

Saves and reloads the trained model.

Visualizes predictions on sample test images.

📌 How to Run (in Colab)

Open the project notebook in Google Colab.

Run the cells step by step:

Import libraries

Load and preprocess the dataset

Define the neural network model

Train the model

Test the model and check accuracy

Save and load the trained model

Visualize predictions on test digits

Accuracy will be printed after evaluation.

Prediction results are shown with images and labels.

📊 Results

Typical accuracy: 95–98% with a simple feedforward neural network.

Most digits are correctly classified, with occasional confusion in similar digits (like 4 and 9).

🔮 Future Enhancements

Use a Convolutional Neural Network (CNN) to achieve ~99% accuracy.

Add a confusion matrix to analyze model errors.

Deploy the model as a web app using Streamlit or Flask for interactive digit recognition.

🏷️ License

This project is created for educational purposes under the MIT License.
