# Facial-Expression-Recognition-in-Keras

Welcome!
Welcome to Facial Expression Recognition in Keras. This is a project-based course which should take approximately 2 hours to finish. Before diving into the project, please take a look at the course objectives and structure:

Course Objectives
In this course, we are going to focus on four learning objectives:

Develop a facial expression recognition model in Keras
Build and train a convolutional neural network (CNN)
Deploy the trained model to a web interface with Flask
Apply the model to real-time video streams and image data
By the end of this course, you will be able to build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. Once you have trained, saved, and exported the CNN, you will directly serve the trained model to a web interface and perform real-time facial expression recognition on video and image data.

Course Structure
This course is divided into 3 parts:

Course Overview: This introductory reading material.
Facial Expression Recognition with Keras: This is the hands on project that we will work on in Rhyme.
Graded Quiz: This is the final assignment that you need to pass in order to finish the course successfully.
Project Structure
The hands on project on Facial Expression Recognition is divided into following tasks:

Task 1: Introduction and Overview
Introduction to the data and and overview of the project.
See a demo of the final product you will build by the end of this project.
Introduction to the Rhyme interface.
Import essential modules and helper functions from NumPy, Matplotlib, and Keras.
Task 2: Explore the Dataset
Display some images from every expression type in the Emotion FER dataset.
Check for class imbalance problems in the training data.
Task 3: Generate Training and Validation Batches
Generate batches of tensor image data with real-time data augmentation.
Specify paths to training and validation image directories and generates batches of augmented data.
Task 4: Create a Convolutional Neural Network (CNN) Model
Design a convolutional neural network with 4 convolution layers and 2 fully connected layers to predict 7 types of facial expressions.
Use Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.
Task 5: Train and Evaluate Model
Train the CNN by invoking the model.fit() method.
Use ModelCheckpoint() to save the weights associated with the higher validation accuracy.
Observe live training loss and accuracy plots in Jupyter Notebook for Keras.
Task 6: Save and Serialize Model as JSON String
Sometimes, you are only interested in the architecture of the model, and you don't need to save the weight values or the optimizer.
Use to_json(), which uses a JSON string, to store the model architecture.
Task 7: Create a Flask App to Serve Predictions
Use open-source code from "Video Streaming with Flask Example" to create a flask app to serve the model's prediction images directly to a web interface.
Task 8: Create a Class to Output Model Predictions
Create a FacialExpressionModel class to load the model from the JSON file, load the trained weights into the model, and predict facial expressions.
Task 9: Design an HTML Template for the Flask App
Design a basic template in HTML to create the layout for the Flask app.
Task 10: Use Model to Recognize Facial Expressions in Videos
Run the main.py script to create the Flask app and serve the model's predictions to a web interface.
Apply the model to saved videos on disk.
Meet the Instructor
I'm Snehan Kekre, a machine learning and data science instructor at Rhyme. I will graduate in 2021 with a BSc in Computer Science and Artificial Intelligence from Minerva Schools at KGI, based in San Francisco. My passion to grow the ML and AI community drives me to create accessible, skills-based, machine learning projects at Rhyme.

About Rhyme
This course runs on Coursera's hands-on platform called Rhyme. On Rhyme, you do projects in a hands-on manner in your browser. You will get instant access to pre-configured cloud desktops that have all the software and data you will need. So, you can just focus on the learning. For this project, this means instant access to a cloud desktop with Python, Jupyter, and TensorFlow pre-installed.

If you need help troubleshooting Rhyme, please refer to the Coursera Help Center for more information.

Earn a Certificate
After you have completed the Facial Expression Regcognition with Keras hands-on project, you will be able to assess your knowledge using an ungraded assignment. Once you are comfortable with the concepts, take the final quiz, score higher than 80% to earn your certificate.


Facial Expression Recognition with Keras
Now we will build and train a convolutional neural network (CNN) in Keras from scratch to recognize facial expressions. We will accomplish it by completing each task in the project:

Task 1: Introduction and Overview
Task 2 : Explore the Dataset
Task 3: Generate Training and Validation Batches
Task 4: Create a Convolutional Neural Network (CNN) Model
Task 5: Train and Evaluate Model
Task 6: Represent Model as JSON String
Task 7: Create a Flask App to Serve Predictions
Task 8: Design an HTML Template for the Flask App
Task 9: Use Model to Recognize Facial Expressions in Videos
While you are watching me work on each step, you will get a cloud desktop with all the required software pre-installed. This will allow you to follow along the instructions to complete the above mentioned tasks. After all, we learn best with active, hands-on learning.

Ready to get started? Click on the button below to launch the project on Rhyme.

Este curso usa uma ferramenta de terceiros, Facial Expression Recognition with Keras, para melhorar sua experiência de aprendizado. A ferramenta referenciará informações básicas, como seu nome, e-mail e sua ID do Coursera.
