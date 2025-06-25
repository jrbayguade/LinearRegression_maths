#### **Least Squares Regression line**

I have to ackowledge the first time I read and understood a linear regression I found it incredibly simple but smart at the same time. Just fascinating. So I wanted to play a bit with the concept.

In this code we will explore how to create a basic lineal regression "manually", this is, without using any built in function in Python. I don't pretend to make this code more efficient or better by any means... I just want to do this exercise to better understand the underlying beautiful maths behind a linear regression. I won't even use a "mean" function, the idea is to do everything as manual as the code allows it.

The aim of a linear regression is to establish the potential correlation between a variable (or multiple variables) and a dependent variable. The line can be then used to predict values that are not in the initial dataset.

The method uses the **least squares method**, which basically aims to minimise the sum of the vertical distance between all of the data points and the line of best fit. This is kind of create the line that fits better the available data. 
