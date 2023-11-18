# Linear Regression Model

This project is a linear regression model to predict a students final grade based on x number of input variables about kids in a portugese school.

The dataset provides 33 different datapoints about kids in the school shown below:
school, sex, age, address, famsize, Pstatus, Medu, Fedu, Mjob, Fjob, reason, guardian, traveltime, studytime, failures, schoolsup, famsup, paid, activities, nursery, higher, internet, G3romantic, famrel, freetime, goout, Dalc, Walc, health, absences, G1, G2, G3

Of which I chose 6 datapoints to use in 5 dimentions for my linear regression model and chose to predict G3 which is the students 'final grade'.
'G1','G2','G3','studytime','failures', 'absences'

The model had its highest accuracy of 95.4% success on predicting final grade (obviously tested on data it hadn't been trained on).

This project uses libraries:
Pandas, Sklearn, Numpy, Pickle (to save the best performing linear regression model) and MatPlotLib (only to plot the graphs)

install all of these libraries by using the following commands:

pip (/ pip3 / pip3.10) install {name}

where {name} is one from: pandas, sklearn, numpy, pickle or matplotlib 
