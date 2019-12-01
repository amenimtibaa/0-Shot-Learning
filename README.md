# 0-Shot-Learning  
training a Siamese Neural Networks for Image Recognition task (using cifar10 dataset).  
The target of zero-shot learning is to classify unseen classes without a single training example.  
I used 5 classes to learn and tested on the overall classes using transfer learning of ResNet50 (50 layer Residual Network): I fixed the weights for the convolutional base and trained only the fully connected layers.  
I achieved 0.32 accuracy using the _contrastive loss_.  
