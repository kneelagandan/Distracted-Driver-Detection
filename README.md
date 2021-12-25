# Capstone-Project 2 - Distracted Driver Detection


Problem Statement:

According to the CDC motor vehicle safety division,
one in five car accidents is caused by a
distracted driver. Sadly, this translates to 425,000 people injured and 3,000 people killed by
distracted driving every year.
State Farm
hopes to improve these alarming statistics, and better insure their customers, by
testing whether dashboard cameras can automatically detect drivers engaging in distracted
behaviors. Given a dataset of 2D dashboard camera images, State Farm is challenging Kagglers to
classify each driver's behavior. Are they driving attentively, wearing their seatbelt, or taking a selfie
with their friends in the backseat?
Dataset contains driver images, each taken in a car with a driver doing something in the car
(texting, eating, talking on the phone, makeup, reaching behind, etc
Goal is to predict the likelihood of what the driver is doing in each picture.

Models to be used: Using Convolutional Neural Networks and Transfer Learning (VGG16)

Framework: Keras version

Loss: Categorical Cross Entropy

Metrics to be used: Accuracy, Precision, Recall, F1 score & Heatmap (Validation Train Predict Vs
Validation Target)

Optimizer: rmsprop

Checkpoint:Model checkpoint by monitoring val_accuracy ’ and storing best weights

Output activation type:softmax

Machine Learning Algorithm Used:Deep Learning – Keras

Conclusion:

This work has looked at solving the detection of distracted drivers through images obtained from the
State Farm Distracted Driver Detection competition on Kaggle.
By using a CNN model was able to achieve 99.5% accuracy on test data.
Despite given the task of classifying very specific classes, the model is evidently able to accomplish
that with great success.
Further evaluation revealed that the most miss
labeled class was reaching behind, often confused
with the driver talking on their phone with the right hand. Overall, the model has proven to be very
effective at predicting distracted drivers, and will hopefully, one day, aid in preventing further injuries
and deaths resulting from distracted driving.

Future Scope of Work:

-Using ImageDataGenerator instead of dimension converter
-Fine tune a few of the lower layers of the VGG16 network by freezing them and retraining the
remaining ones.
-Using Restnet model for training & predicting

Final Report : [Capstone2_presentation.pdf](https://github.com/kneelagandan/Distracted-Driver-Detection/files/7775476/Capstone2_presentation.pdf)
