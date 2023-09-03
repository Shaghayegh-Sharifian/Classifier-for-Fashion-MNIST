# Classifier for Fashion MNIST Dataset<br>
## **Overview**
In this code, I pre-processed and built models for Fashion Minist Dataset classification.<br>
In my first model, I only **used Dense (fully connected) networks**, which brought about:<br>
Final test set loss: 0.383466<br>
Final test set accuracy: 0.867000<br>
<br>
In my second model, I used **Convolutional classifications**, including 3 Convolutional layers and also 3 pooling levels while having 1 fully connected layer:<br>
Final test set loss: 0.689769<br>
Final test set accuracy: 0.904400<br>
<br>
## **Conclusion**<br>
Even though the test set accuracy result was satisfying, but accuracy and test outputs in the plots show overfitting in my model.<br>
Consequently, I used **Early Stopping callback** to avoid overfitting in my neural network; I also saved the best model to load and evaluate at any time in the future.<br>
The output of my third model:<br>
Final test set loss: 0.286987<br>
Final test set accuracy: 0.898800<br>
