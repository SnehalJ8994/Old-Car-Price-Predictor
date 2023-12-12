# Old-Car-Price-Predictor

Presentation Video: https://www.youtube.com/watch?v=t5FJUxC1o5k

![image](https://github.com/SnehalJ8994/Old-Car-Price-Predictor/assets/118697221/1c04d70d-5560-4ca3-987b-4d8933f1ead1)

# Goal
This project acts as a middleman between a “customer” and a “car owner” to help to get a better price for the old car. 
It uses specific details of a pre-owned vehicle, like the manufacturer, model, year of purchase, fuel type, and kilometers driven, to estimate the vehicle's current market value.


# How to use?
1. Clone the Repository: Clone this repository to your local machine.
2. Install Required Packages: Install the packages listed in the "requirements.txt" file. Key packages include:
   
numpy

pandas
          
scikit-learn (You will need updated version to run this application)

4. Run Application: Execute the "application.py" file to start the application





# Description:

This initiative leverages data scraped from Quikr.com. The data, initially unclean with format errors, was thoroughly cleaned and analyzed. A Linear Regression model was then developed, achieving an R2 score of 0.57. This model is used in a Flask-based web application to make price predictions.


# How this project created?

1. First of all the data was scraped from Quikr.com (https://quikr.com) Link for data: https://github.com/SnehalJ8994/Old-Car-Price-Predictor/blob/main/quikr_car.csv
2. The data was cleaned (it was unclean and had lots of format errors) and analysed.
3. Then a Linear Regression model was built on top of it which had 0.57 R2_score.
4. Link for notebook:https://github.com/SnehalJ8994/Old-Car-Price-Predictor/blob/main/CAR%20Price%20Predictor%20Updated.ipynb
5. This initiative was developed as a website utilizing Flask, where the Linear Regression model is employed to carry out the predictions.
