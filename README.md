# Optical-Character-Recognition

The given dataset contains 1000 images and each image contains 5 characters which are all alphabets. I split the image into the characters and did character recognition. In the end, using the trained model I tried to predict characters in different images entirely and thereby checking the robustness of the system in the recognition phase.

1. Performed various techniques such as thresholding, dilation, and erosion to improve the quality of images.
2. Once, all the images have been preprocessed, they were split into individual characters.
3. Trained the model using these three ML algorithms - Logistic Regression, Support Vector Machine, and Random Forest for the classification task. For the above-mentioned algorithms, various scores were calculated to analyze their performance after hyperparameter tuning.
4. Trained a deep neural network (CNN) that works better than all these ML Algorithms.


After the model was fit, the following questions were addressed:
1. Which of the above classifiers yields the best accuracy on the validation set? Do you think accuracy is the best metric to compare
the algorithms, if not - which other metrics could be used?
2. Tweak the hyperparameters of the classifier selected in Q1 and try to improve the accuracy. What hyperparameters did you
change, and why do you think it worked?
3. Find Precision, Recall, and F1 score in all cases.
4. a. Find the confusion matrix using the best classifier. 
b. Which characters have low accuracy? 
c. What can be the reason for this? 
5. Try any other techniques/algorithms in your research that could improve the accuracy. 
