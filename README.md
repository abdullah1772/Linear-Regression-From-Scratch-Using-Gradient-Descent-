# Linear-Regression-From-Scratch-Using-Gradient-Descent-

Let us consider now the model given by  F(x,w1,w2)=w1+w2x which has two parameters  w1 and  w2 We want to adjust the values of  w1 and  w2 so that  F is a good approximation of the 'data'  Y
a. Write a python function that takes as arguments 𝑋 and 𝑌 , and returns the mean square error of 𝐹 given by 𝐸(𝑤1,𝑤2)=1𝑁∑𝑖=1𝑁(𝑤1+𝑤2𝑥𝑖−𝑦𝑖)2
b. Calculate the gradient of 𝐸(𝑤1,𝑤2) analytically. 
c. Using the function of the previous item, implement a gradient descent algorithm that can estimate good values of 𝑤1 and 𝑤2 .
