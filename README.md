
<div align = "center">

# Deep-Learning-Challenge


</div>

The Modle demonstrates a steady improvement in accracy over the epochs, maintaining a constant accuracy around 0.72. There is a minimal overfitting but not substaintial gap between training accracy and validation accuracy. suggesting that the model is not severly overfitting the training data.

I run the model a total of 5 times with a different hidden layers , different units and dropouts to optimize the accuracy.however it plateaued, modification such as adjusting the learning rate, increasing the model complexity, employing technique like dropout for regularization might help in achieving an accuracy close to 0.75.

Overall the accuracy is about 72% means that the model correctly predicts  the outcome 72% times of the time on the test data.

The result from the diffenrent runs are as follows:

First Run

- Number of hidden layers = 2
- units 80 and 30
- Accuracy =0.7265
  
second Run 
- Number of hidden layers = 4
- units 128,80,64 and 32 with a dropout of 0.2
- Accuracy = 0.7277
  
Third Run

- Number of hidden layers = 1 
- units = 80
- Accuracy = 0.7292

Fourth Run
- Number of hidden layers = 1
- units = 128 and a dropout of 0.3
- Accracy = 0.7286

Fifth Run

- Number of hidden layers = 2
- units = 256 and 128 with a dropout of 0.3
- Accracy = 0.7248
