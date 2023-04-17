# Infosys-Stock-Price-Prediction-using-LSTM-and-BiLSTM
In this project, we have analyzed 22 years of historical data from Infosys, spanning from 2000 to 2022, using machine learning algorithms. Additionally, we have applied deep learning techniques such as LSTM and Bi-LSTM to extract insights from the data.

For this Project, we collected the dataset from  https://finance.yahoo.com/ .

Firstly, we have done some preprocessing and applied machine learning algorithms.
Algorithms:
1. Linear Regression : Mean Squared Error(MSE)= 0.025
2. Support Vector Machine(SVM) : Mean Squared Error(MSE)= 0.031
3. Decision Tree Regressor : Mean Squared Error(MSE)= 0.0078
4. Random Forest Regressor : Mean Squared Error(MSE)= 0.0044


Secondly, We applied Neural Networks to predict the price, by using LSTM(Long Short Term Memory) which is the extension of RNN(Recurrent neural network)

Accuracy : 98%  , loss : 1.0279e-04

![Screenshot (15)](https://user-images.githubusercontent.com/94118977/232517692-ff98ec25-792c-46e0-a1fd-4a0b7ef2062c.png)

Lastly, We applied BiLSTM(Birectional Long Short Term Memory) which is extension of LSTM

loss : 8.3488e-05 


![Screenshot (14)](https://user-images.githubusercontent.com/94118977/232518232-aba7a7f3-1ff9-4880-9dec-2a63ae88c2eb.png)
![Screenshot (13)](https://user-images.githubusercontent.com/94118977/232518261-868480ee-7945-4713-9d48-00aa35d61de0.png)


