# Project Scope</br>
* Project diving into whether a college education is worth the expense of attending by Andrew Matsura and Holly Miesbauer </br>

## Overview </br>
*There have been multiple studies completed demonstrating that indeed one's lifetime earnings for the college educated exceed that of non college educated individuals. 
*Overall, a college education is worth it in terms of a return on investment over one's lifetime in terms of earnings, however, what exactly determines the worth of a college education?
*To that end, we created several deep learning models to look at what features were important in determining a successful ROI for college attendance such as:<br>
  * Public or private
  * Mean earnings six years post graduation
  * Did the student take on student loans? And if so, how much?<br>
    
## Model 1: <br>
* This first model

* Model Architecture With One Output Layer:
  ![Model Architecture](images/https://github.com/andymatsuura/college_salary_prediction/blob/main/Images/Model%20architecture%20Unit%201%20Output%20ROI%20label.PNG)<br>
  
* Model Predictions With One Output Layer:
  ![Predictions with One Output Layer](images/https://github.com/andymatsuura/college_salary_prediction/blob/main/Images/Plot%20Predictions%201%20Unit%20Ouput%20tf%20keras%20model%20label%20ROI.PNG) <br>

## Model 2: <br>
* The second model



![Random Forest](images/https://github.com/andymatsuura/college_salary_prediction/blob/main/Images/Model%202%20Random%20Forest.PNG)<br>


## Model 3: <br>
* In this model, to correct for loss leakage drop out rates were added:
    256/256 [==============================] - 1s 3ms/step
    256/256 - 1s - loss: -1.2439e+10 - accuracy: 0.9422 - 952ms/epoch - 4ms/step
    Loss: -12438753280.0, Accuracy: 0.9422417879104614


## Model 4 Final Model: <br>

  






















# Works Cited </br>
* [Knox magazine]((https://www.knox.edu/magazine/spring-2018/features/yes-college-is-worth-it))

# Data and Research Sources </br>
* Dataset for this project was dowloaded [here]((https://www.kaggle.com/datasets/kaggle/college-scorecard?resource=download&select=Scorecard.csv))
