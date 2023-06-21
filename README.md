# Optical-Character-Recognition

The given dataset contains 1000 images and each image contains 5 characters which are all alphabets. I split the image into the characters and did character recognition. In the end, using the trained model I tried to predict characters in different images entirely and thereby checking the robustness of the system in recognition phase.

1. Performed various techniques such as threshholding, dilation and erosion to improve the quality of images.
2. Once, all the images have been preprocessed, they were split into individual characters.
3. Trained the model using these three ML algorithms - Logistic Regression, Support Vector Machine, Random Forest for the classification task. For the above mentioned algorithms, various scores were calculated to analyse their performance after hyperparameter tuning.
4. Trained a deep neural network (CNN) that works better than all these ML Algorithms.
