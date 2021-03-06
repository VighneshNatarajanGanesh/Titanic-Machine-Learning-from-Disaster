# Titanic-Machine-Learning-from-Disaster
The above folder has the code to analyze the Titanic disaster problem using neural network. This dataset performs better with arguably simpler algorithms like Random forests but since this was the first dataset I ever explored, I wanted to start keras in it.

## Different accuracy scores with different NN sizes: ##

 iteration over different NN sizes:

 |Hidden layer size   |train_loss    |train_accuracy   |dev_loss   |dev_accuracy  |dropout          | Inference               |
 |--------------------|--------------|-----------------|-----------|--------------|-----------------|-------------------------|
 |15 10 10 10         |0.4592        |0.8069           |0.4386     |0.7982        |no overfitting   |                         |
 |15 10               |0.4171        |0.8204           |0.4153     |0.8161        |no overfitting   |                         |
 |7 5 5               |0.3919        |0.8293           |0.4239     |0.8341        |no overfitting   |                         |
 |20 5                |0.4198        |0.8278           |0.4271     |0.8072        |no overfitting   |                         |
 |25 5                |0.3811        |0.8398           |0.4522     |0.8430        |0.1   0          | 25 best for first layer |  
 |30 5                |0.3948        |0.8308           |0.4024     |0.8341        |0.1   0          |                         |
 |25 5 5              |0.3657        |0.8473           |0.4108     |0.8430        |0.1   0          | even better!!!          |
