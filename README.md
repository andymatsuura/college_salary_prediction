# Project Scope</br>
* Project diving into whether a college education is worth the expense of attending by Andrew Matsura and Holly Miesbauer </br>

## Overview </br>
* There have been multiple studies completed demonstrating that indeed one's lifetime earnings for the college educated exceed that of non college educated individuals <br>
* Overall, a college education is worth it in terms of a return on investment over one's lifetime in terms of earnings, however, what exactly determines the worth of a college education?<br>
* To that end, we created several deep learning models to look at what features were important in determining a successful ROI for college attendance such as (but not inclusive):<br>
  * Is the institution Public or private
  * What are the mean earnings six years post graduation
  * Did the student take on student loans? And if so, how much?<br>
   
## Model 1: <br>

* Model Architecture With One Output Layer:<br>
  ![Model Architecture](https://github.com/andymatsuura/college_salary_prediction/blob/main/Images/Model%20architecture%20Unit%201%20Output%20ROI%20label.PNG)<br>
  
* Model Predictions With One Output Layer:<br>
  ![Predictions with One Output Layer](https://github.com/andymatsuura/college_salary_prediction/raw/main/Images/Plot%20Predictions%201%20Unit%20Ouput%20tf%20keras%20model%20label%20ROI.PNG)
 <br>

## Model 2: <br>
* The second model was compiled with Random Forest with one output layer and the same features of model 1<br>

* Top Feature Importances:<br>
![Top Feature Importances](https://github.com/andymatsuura/college_salary_prediction/raw/main/Images/Images/Top%20Feature%20Importances%20Random%20Forest.PNG)
<br>

* Model Predictions With One Output Layer:<br>
![Random Forest](https://github.com/andymatsuura/college_salary_prediction/raw/main/Images/Model%202%20Random%20Forest.PNG)
<br>

* Model evaluation: <br>
  * Mean Absolute Error: 68202.69008352426
  * Mean Squared Error: 9290541773.416914
  * Root Mean Squared Error: 96387.45651492685 <br>

## Model 3: <br>
* In this model, to correct for loss leakage drop out rates were added and a second output layer added to improve accuracy:
![Model Plot](https://github.com/andymatsuura/college_salary_prediction/raw/main/Images/Images/Model%203%20increase%20output%20layer%20add%20dropout%20rates.PNG)<br>

* Model Evaluation: <br>
 * 256/256 - 0s - loss: -2.0165e+03
 * - accuracy: 0.9422
 * - 347ms/epoch - 1ms/step
 * Loss: -2016.5423583984375
 * Accuracy: 0.9422417879104614 <br>
 * Mean Absolute Error: 130.5268270320259
 * Mean Squared Error: 369534.07959854195
 * R-squared: -405.8856610447764
![Model Evaluation](https://github.com/andymatsuura/college_salary_prediction/blob/main/Images/Images/Model%203%20Evaluation%20Metrics.PNG)
  

## Model 4 Final Model: <br>

  
















# Conclusion: <br>
* Modeling is an iterative process
* Changing items such as the features our models were using, most notably adding drop out rates, and increasing training time all contributed to small improvements in the models

# Works Cited </br>
* [Knox magazine](https://www.knox.edu/magazine/spring-2018/features/yes-college-is-worth-it))<br>

# Data and Research Sources </br>
* Dataset for this project was downloaded [here](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset?select=ratings.csv)<br>
