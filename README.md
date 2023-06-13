# Lifespan_of_a_Building
Buildings and structures are designed to contain and support certain load, but nowadays we often see huge structures failing catastrophically resulting in death of thousands of people.

This can be avoided if we can predict life span of a building by comparing against range of parameters
_____________
Objective:
To predict lifetime of a building by training a machine learning based model and also depict possibility of a building collapse. 
______________________
Requirements:
Programming: Python
IDE: Jupyter Notebook & VS CODE
(Including python libraries such as: matplotlib, numpy, scipy, scikit-learn & Flask )
___________________
>Access and read the data set which includes all raw data of the various parameters and use it in csv format if provided initially in exel format.

>Divide the data set into two parts ( split into train set and test set ) and using StratifiedShuffle Split a shuffled variation of values are used

>Finding the correlation between the parameters (Strong/weak   positive/negative correlation)

>To check if there are any missing attributes and get rid of missing data points or assign values to the missing data points using median and imputer

>Create pipeline and select desired model by fitting and trying out different models(Decision Tree, Linear, Random Forest Regressor)

>Evaluate the model and save the model for testing 

_______________________________-
A decent UI is also made (tested in postman) for the user to just enter the values for the required parameters and then the predicted output is shown.

future commits will include docker code as well and be depeloyed on netlify.