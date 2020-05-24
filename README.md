# Neural Network from scratch

In this project I've followed the tutorial from Tariq Rashid's book - How to make your own neural network.

It's a shallow 3 layer network, using stochastic gradient descent, trained on the mnist handwritten dataset, and has achieved a maximum accuracy of 98.93%. While the notebook shows 93%, it's to demonstrate that 5 epochs can get you an accuracy that high.
You can tune hyperparameters to obtain that 98%, and if it doesn't work, here are the hyperparameters values you should try:

lr = 0.01

epochs = 25

hidden_nodes = 150

These values should get you an accuracy figure close to 98%.
