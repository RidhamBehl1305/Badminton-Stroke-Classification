# Badminton-Stroke-Classification
Defining the problem

To start off, we first need to define and properly formulate the problem we want to solve. Since, this was a course project we could have chosen any problem. We finalized to work on classifying the kind of stroke a player is playing based on the sensor's data we get from her smartwatch. This was an extension of Human Activity Recognition (HAR) project, which using similar data, classifies the activities as running, walking, etc. In our case, we decided to have the following badminton strokes as classes:

Backhand Overarm (bo)

Backhand Underarm (bu)

Forehand Overarm (fo)

Forehand Underarm (fu)

Forehand Smash (fs)

Methodology
Data Cleaning -> Saving processed data

Adding features to classic ML models

Classic ML models used:

	1.Logistic regression
  
	2.K nearest neighbpours
  
	3.Linear SVC
  
	4.SVC with RBF kernel
  
	5.Random forest
  
	6.Gradient boosting
  
Deep learning models:

	1.LSTM

Input -> accelerometer and gyroscope readings over a period of time at a decent frequency

Output -> various classification outputs

![image](https://user-images.githubusercontent.com/106107245/208173019-d619b581-4255-445c-a837-24b04c3c08bd.png)


Live Link

https://github.com/RidhamBehl1305/Badminton-Stroke-Classification/blob/main/notebook.ipynb
