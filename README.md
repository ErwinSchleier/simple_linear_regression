# Simple Linear Regression

## Introduction

This notebook provides a case study for a simple linear regression. With a dataset containing several output records of a solar farm and temperature measurements. We are building a model which is able to predict the daily output with a temperature value as input. This is an excellent case study as it represents a real world problem and includes some data preparation in advance.

A simple linear regression discovers the relationship between two variables. A so called independent variable X, which is used for predictions, in our case  temperature values and a dependent variable Y which is the value of interest, our output values. The math behind it is quite straight forward: 
$$ Y = a + bX$$
In addition to Y and X we are adding an intercept a, which is a constant. The intercept would be Y if X is zero. And a slope b which defines how strong Y rises or falls when X changes.

## Installation
Clone the repository to your local machine
```
git clone https://github.com/ErwinSchleier/simple_linear_regression.git
```

I recommend to create a virtual environment with the python library virtualenv or anaconda.

Install all required pip libraries
```
pip install -r requirements.txt
```

Start jupyter notebook inside the repository direction
```
jupyter notebook
```

