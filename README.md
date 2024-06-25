# LINEAR-MODELS-FOR-REGRESSION-AND-CLASSIFICATION

Project details:

This project aims to help gain hands-on experience by developing and applying appropriate machine 
learning models. Assess the correct application of 
the respective machine learning technique and the interpretation of the results obtained. 

1. Stochastic Gradient Descent and Batch Gradient Descent using Linear Regression

2. Lasso and Ridge Regression using Polynomial Regression
 
3. Logistic Regression and Least Squares Classification

Dataset:

The Diabetes dataset given contains the following features. It is used to predict which patient is diabetic 
based on the analysis of the patient’s history and key medical factors.

1. No. of Pregnancies: To express the number of pregnancies
   
2. Glucose level: To express the Glucose level in blood
 
3. Blood Pressure: To express the Blood pressure measurement
 
4. Thickness of Skin: To express the thickness of the skin

5. Insulin level: To express the Insulin level in blood
 
6. BMI: To express the Body mass index

7. Diabetes Pedigree Function: To express the Diabetes percentage. DPF calculates diabetes 
likelihood depending on the subject's age and their diabetic family history.

8. Age: To express the age
 
9. Outcome: To express if the person is diabetic; 1 is Yes and 0 is No

Insights:

1. Comparison of Stochastic Gradient Descent and Batch Gradient Descent using Linear Regression


We can see from above analysis that SGD algorithm takes longer time than compared to BGD but SGD has the higher accuracy. In summary, BGD uses the entire dataset in each iteration and converges more smoothly, while SGD processes individual data points or mini-batches and converges noisily but may converge faster and be more efficient for large datasets.

2. Comparison of Lasso and Ridge Regression using Polynomial Regression

   
Ridge primarily addresses the issue of multicollinearity and helps control the model's variance. It can lead to a slight increase in bias compared to an unregularized model. Lasso addresses multicollinearity and offers feature selection, but it can introduce more bias compared to Ridge due to its sparsity-inducing nature and we can also see from above analysis that mean sqaured error of ridge regression is less compared to lasso regression.

3.Comparison of Logistic Regression and Least Squares Classification


We can see Logistic regression results is comparable to those of least square regression, but gives more accurate predictions of probabilities on the dependent outcome. Least square regression is accurate in predicting continuous values from dependent variables.This can be proved from above analysis as logistic regression has accuracy of 69% where as least sqaure classification accuracy is comparable to logistic but a less(63%).


References

https://docs.sdv.dev/sdv/

https://numpy.org/doc/stable/reference/generated/numpy.exp.html

https://pandas.pydata.org/docs/reference/general_functions.html

https://matplotlib.org/stable/gallery/index.html
