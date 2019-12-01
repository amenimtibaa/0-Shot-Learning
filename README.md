# 0-Shot-Learning  
training a Siamese Neural Networks for Image Recognition task(using cifar10 dataset).  
The dataset contains 10 classes, we used 5 classes to learn and tested on the overall classes.  
We used transfer learning with ResNet50, we fixed the weights for the convolutional base layers and we trained only the fully connected layers.  
We achieved 0.32 accuracy using _contrastive loss_.  
