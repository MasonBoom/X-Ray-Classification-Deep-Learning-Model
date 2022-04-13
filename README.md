# X-Ray-Classification-Deep-Learning-Model

This project was completed to fulfill the requirements of Codecademy's "Build Deep Learning Models with TensorFlow" skill path. The project's goal was to build a deep learning model of x-ray lung scans to determine if a patient has pneumonia, COVID-19, or no pulmonary illness. More specifically, I built a classification model using TensorFlow and Keras which produces a diagnosis based on a patient's chest x-ray scan. 

I have included in this repository the code used to build, train, and evaluate my deep learning model as "x-ray_classification_challenge_MAC.py." The code was written in Python 3.8. In writing my code, I used the most recent version (to the best of my knowledge) of the libraries os, TensorFlow, random, NumPy, Matplotlib, and scikit-learn. Under the hood, I also used the pillow library, though I found that I did not need to explicitly import PIL into my code. I attempted to initialize random seed settings, and in order to do so my code should be run with the following command: PYTHONHASHSEED=0 python x-ray_classification_challenge_MAC.py I recommend running from the IDLE environment.

The data supplied in this project is from the following link: https://www.kaggle.com/pranavraikokte/covid19-image-dataset
