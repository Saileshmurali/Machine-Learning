# Machine-Learning
Repository Containing works related to ML/DL in google colab.

Handwritten Digit Recognition
1. Has CNN model with and without data augmentation to classify handwritten digit's images
2. Has the dataset used in excel format
3. Using Random forest and SVM. CNN is usually preferred, just tried it out.
4. CNN without Augmentation, predicting the bounding boxes along with class (object detection and classfication). 

Image Segmentation Using CNN
1. Has python notebook code for training a CNN used for image segmentation. The encoder part used VGG-16 architecture and pre-trained weights.

Keyword Spotter using CNN
1. The CNN model is used to detect keywords (yes/no/silent/background) using google speech dataset.
2. Audio are sampled at 16KHz. Spectrogram computed using pre-existing code is fed as input to the model
3. Also contains the output .h5 (floating point weights & biases) and .tflite (int8_t datatype for weights and biases)
4. Can visualize the model through Netron
