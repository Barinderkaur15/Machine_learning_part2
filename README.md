# Machine_learning_part2
 
 
**How many neurons and layers did you select for your neural network model? Why?**

**1.Input Layer** : Added no. of input features equal to the number of variables in the feature DataFrame. <BR>

**2.Hidden layers**  :  Added two hidden layers (following the similar steps in Module). <BR>

Hidden layer  use the relu activation function to identify nonlinear characteristics from the input values.
for the output layer,  parameters from basic neural network is includded with  the sigmoid activation function. <BR>

The sigmoid activation function, also called the logistic function, is traditionally a very popular activation function for neural networks. The input to the function is transformed into a value between 0.0 and 1.0.<BR>

The sigmoid activation function will predict whether or not an applicant will be successful if funded by Alphabet Soup organisation . <BR>

**Were you able to achieve the target model performance? What steps did you take to try and increase model performance?**

After  training and fitting the model with 100 epochs , the model shows 72.4% of accuarcy.
The deep learning model was able to produce a fairly reliable classifier but the accuracy is not very good .
To increase the accuracy 
step 1 : Number of Epocs were incresed but model doesnot show any significant change in accuracy <BR>
step 2 : Number of hidden layers were increased which helped model little bit from accuracy count of 72.4% it reaches to 72.6% .

Adding more epochs to the training parameters is not a perfect solution—if the model produces weight coefficients that are too effective, there is an increased risk of model overfitting. <BR>
After using two trial pattern method the model is not able to reach the predective accauracy higher then 75% <BR>
Because of lack of time and deadline other methods to check noise in data is not used , which can help in increasing the performance <BR>

**If you were to implement a different model to solve this classification problem, which would you choose? Why?**
Random Forset Method 
Random forest classifiers are a type of ensemble learning model that combines multiple smaller models into a more robust and accurate model.Both output and feature selection of random forest models are easy to interpret, and they can easily handle outliers and nonlinear data.Hence Random forest models have been a staple in machine learning algorithms for many years due to their robustness and scalability
