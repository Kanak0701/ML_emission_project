# ML_emission_project
POLARIS
PROBLEM STATEMENT :
To study and predict the carbon-dioxide emission of various
automobiles based on attributes like no. of cylinders,engine size and
fuel consumption as well as to classify them into high, average and
low carbon emitting automobiles .To calculate the no of trees required
to nullify the effect of the carbon-emission of a given vehicle in a given
period of time.
INTRODUCTION:
Our project is to study and evaluate the dataset containing information
about the carbon emission of various automobiles with attributes
differentiating them on the basis of engine-size, fuel type, model and
make of the vehicle and fuel consumption.
The carbon emission of a particular automobile is calculated on the
basis of no. of cylinders,engine size and fuel consumption.
The algorithm used to predict whether the carbon emission falls into
the category of high, average or low is K-means clustering which is
used to classify them into the above mentioned categories.
Moreover we have used multiple regression using dependent
variables as co2 emissions and independent variables being no. of
cylinders,engine size and fuel consumption to predict co2 emissions.
The model also calculates the no of trees required to nullify the effect
of co2 emitted by a particular automobile over a given period of time
which is taken from the user .

The model also uses heat map to show the co-relation between
various attributes used in the dataset.
The heat map indicates which attributes are highly co-related thus
giving a comprehension regarding the effect of a particular attribute on
its other attributes.
Using test data and the predicted value the model calculates mean
absolute error to get the accuracy of the model which is 94.41%.
This provides an insight to the user as to how much fuel consumption
emits what amount of carbon as well as the no of trees required to
annul that effect caused to the environment.
We have used flask module to provide a GUI to our model.Flask
libraries like request,render_template,redirect,session,url_for
are used to provide an interface to our model for user access.

Link to the dataset:
https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-ve
hicles

Our dataset contains attributes pertaining to : Make,Model,Vehicle
class,Fuel Consumption,Engine size, Cylinders
