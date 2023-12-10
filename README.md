# Old-Car-Price-Predictor

Presentation Video: https://www.youtube.com/watch?v=t5FJUxC1o5k

![image](https://github.com/SnehalJ8994/Old-Car-Price-Predictor/assets/118697221/1c04d70d-5560-4ca3-987b-4d8933f1ead1)

Goal: This project acts as a middleman between a “customer” and a “car owner” to help to get a better price for the old car.


# How to use?

Clone the repository
Install the required packages in "requirements.txt" file.
Some packages are:
numpy
pandas
scikit-learn (You will need updated version to run this application)
Run the "application.py" file And you are good to go.


# Description:

This initiative utilizes specific details of a pre-owned vehicle, such as the manufacturer, model, year of purchase, fuel type, and KMs driven. Leveraging this data, it estimates the vehicle's current market value.


# How this project created?

1. First of all the data was scraped from Quikr.com (https://quikr.com) Link for data: add
2. The data was cleaned (it was unclean and had lots of format errors) and analysed.
3. Then a Linear Regression model was built on top of it which had 0.92 R2_score.
4. Link for notebook:
5. This initiative was developed as a website utilizing Flask, where the Linear Regression model is employed to carry out the predictions.
