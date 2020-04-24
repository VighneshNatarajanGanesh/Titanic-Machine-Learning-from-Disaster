#Readme#
This is the first version of the solution with no data augmentation. It is just a simple and quick solution using keras

##Different accuracy scores with different models:##

 iteration over different NN sizes:

# size                train_loss    train_accuracy    dev_loss   dev_accuracy  dropout           inference
# 15 10 10 10 1 ..... 0.4592        0.8069            0.4386     0.7982        no overfitting    
# 15 10 1 ........... 0.4171        0.8204            0.4153     0.8161        no overfitting     
# 7 5 5 1 ........... 0.3919        0.8293            0.4239     0.8341        no overfitting     
# 20 5 1 ............ 0.4198        0.8278            0.4271     0.8072        no overfitting     
# 25 5 1 ............ 0.3811        0.8398            0.4522     0.8430        0.1 0             25 best for first layer    
# 30 5 1 ............ 0.3948        0.8308            0.4024     0.8341        0.1 0
# 25 5 5 1 .......... 0.3657        0.8473            0.4108     0.8430        0.1 0  
