# Transfer Learning for AlexNet on CIFAR-10
This notebook implements transfer learning for AlexNet on the CIFAR-10 dataset.

# Key Points

Model: AlexNet architecture is used as a starting point.
Fine-tuning: All parameters in AlexNet are frozen except for the final classification layer.
Output Layer: The final 1000-class layer is replaced with a new linear layer with 10 outputs, corresponding to the 10 classes in CIFAR-10.
Accuracy: Achieves an accuracy of approximately 0.8 on the CIFAR-10 test set.
# Contents

The notebook details the process of:
Downloading and pre-processing the CIFAR-10 dataset.
Loading the pre-trained AlexNet model.
Freezing all layers except the final classification layer.
Adding a new linear layer with 10 outputs for CIFAR-10 classification.
Training the model on the CIFAR-10 dataset.
Evaluating the model's performance on the test set.
