
**Food 101**

The Food101 dataset can be downloaded as a TensorFlow dataset using the code below or directly from the [Kaggle page]("https://www.kaggle.com/datasets/dansbecker/food-101").

The notebook performs the following steps:

1. Downloads the Food101 dataset
2. Preprocesses the images.
3. Augments the training dataset and displays the modified image.
4. Specifies the precision policy.
5. Builds a CNN model based on *EfficientNetB0*. 
6. Trains the model while saving checkpoints and applying early stop rules.
7. Displays the final results, icluding the presentation of misclassified items and the confusion matrix.
