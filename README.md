# Disney World Wait Time Analysis
This project was created as a final project for our Statistical Data Science class which goes over the fundamentals of utilizing IPython for data science, while we adopt the sklearn package to develop machine learning models. Our project is divided into two different IPython notebooks. The first notebook containing our exploratory data analysis, and the second containing our predictions on the data using different machine learning models.

Data obtained was from Disney World's official tour website. It consists of multiple features such as max temperature, parade times, percentage of kids in school per given day, etc.

### Methodology
* Data Preprocessing
* Exploratory Data Analysis
* Feature Engineering
* Heatmaps
* Linear Regression
* Reguralization Techniques
* Random Forest

### Random Forest Modeling Accuracy
<img width="420" alt="Screen Shot 2019-07-07 at 6 15 48 PM" src="https://user-images.githubusercontent.com/30671201/60776762-52484880-a0e3-11e9-9f39-27d3be563b25.png">

### Conclusions
Due to deficiencies in the data, we eliminated the actual wait times for each ride. Chasing out these data points or creating a weighting system for actual wait time data points available could provide a more accurate wait time set to analyze. This could explain the larger gaps in accuracy when defining our model for predicting wait times. However, more problems could arise due to the lack of actual wait times that cause the posted wait time data to have more noise than our results currently display.

It became apparent that due to the summer season being Disney World’s peak season, the average wait times per week, month, and year tended to be higher than Disney World’s low seasons during winter and fall. Wait times during each hour of the day varied by other factors such as parades or fireworks, but did not prove to have a large impact on the overall correlation of wait times for the ride Splash Mountain. This could be due to the gaps in our data in relation to posted wait times and the actual wait times. Dropping Disney World’s actual wait time data from our dataset during feature scaling due to lack thereof could prove to have influenced parade and fireworks times stronger than currently displayed in our analysis.

After testing all models and analyzing each error set, we determined Random Forests to be the best model for determining wait times for the summer. Random Forests contained the lowest of the 5 models tested with a 93.58% relative Mean Squared Error and 0.109323 Mean Squared Error, thus providing us with the closest predictions from the actual wait times to the predicted. The Ordinary Least Squares model was not as precise as the Random Forest model

### Contributors
* Lauren Wong
* Andy Tran
* David Ing
* Derek Chu

### Poster session
<p align="center"> 
<img src="https://i.imgur.com/900umc2.jpg" align="center" width="60%" height="60%">

<p align="center"> 
Missing from image : Lauren Wong
</p>




