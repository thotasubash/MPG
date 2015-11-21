### MPG
Miles Per Gallon
It is a measure of the average distance traveled per unit of energy consumed. 

### Motivation
According to Christopher Knittel, a professor of applied economics at the M.I.T. Sloan School of Management, if weight, horsepower and torque were held to their 1980 levels, and efficiency-boosting technologies continued to be honed — fuel economy for both passenger cars and light trucks would have increased by almost 60 percent from 1980 to 2006, from a present average of 23 miles per gallon across the fleet to approximately 37 m.p.g. 

###Methodology
Using linear model to the mtcars dataset, modelled the effect of horsepower, number of cylinders, and weight of the vehicle on the mpg. Since the valid possibilities for number of cylinders in the dataset were 4, 6, and 8. I have limited the choice using radio buttons.  For the weight, reactive() is used to convert the user input weight into the units used by the model, lb/1000.  Finally, a pre-set function using the linear model is used to predict the mpg based on the three variables input by the user.'
