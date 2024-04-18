# ML-for-AirQuality
Clean air has a significant positive impact on several Sustainable Development Goals (SDGs), such as Good Health and Well-Being, Affordable and Clean Energy and an indirect impact on others.  Using Machine Learning , we can analyse and gain valuable insights on the air quality. 

There are many models and algorithms in Machine learning, each with their own perks. The models implemented are Naive Bayes Classifier , K - Nearest Neighbours (KNN) , Random forest  and Artificial Neural Network (ANN) . All from stracch.
The dataset used is https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set 

Preprocessing: The dataset contains the responses of a gas multisensor device deployed on the field in an Italian city. Hourly responses averages are recorded along with gas concentrations references from a certified analyzer. It contains 9357 instances of hourly averaged responses from an array of 5 metal oxide chemical sensors embedded in an Air Quality Chemical Multisensor Device.
To calculate the AQI from these readings, each reading has been classified into the appropiate AQI values. The overall AQI is calculated as  the maximum of these 4 AQI values. 

Naive Bayes:  47.38% accuracy
KNN: 43.40% accuracy
Random Forest :67.84% accuracy
ANN : 
