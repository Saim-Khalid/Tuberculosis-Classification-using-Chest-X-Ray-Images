# Tuberculosis Classification using Chest X-Ray Images!

![Artboard 1](https://user-images.githubusercontent.com/50315486/207563869-4240d1c2-bbeb-4c8c-b623-181ac1916057.png)


## Scope
Fast and accurate medical diagnoses of tuberculosis is more important than ever. The current computer vision and deep learning technology have made this possible. We applied an EfficientNet model to identify Tuberculosis cases in the test set. After training the model will be able to classify Tuberculosis x-ray images from normal x-ray images.

## Dataset
For classification purpose a public dataset of chest x-ray images is used which can be found here. The dataset contains images of Normal lungs and effected with Tuberculosis. Total number of normal images are 3500 and total number of effected images is 700. For training the dataset is further separated as 70% for training, 20% for testing and 10% for validation for both Normal and Tuberculosis images.

## Classification Overflow
Deep learning based EfficientNet model  with Transfer Learning was trained to classify and identify tuberculosis from chest x-ray. We first set up the configurations. Epoch specifies how many times the model will meet and be trained on the dataset. We also specified the number of samples in each batch. The model is trained by altering the following hyperparameters which are Image Dimensions, Batch_size, No. of Epochs

All the images were resized to 224×224 with batch size of 16 and the model was trained on different number 10, 20 and 30 epochs with same image size and batch size respectively.

## Results:
The model achieved overall good training, testing and validation accuracy, model results can be visualized as follows

**Confusion Matrix**

<img width="582" alt="Screenshot 2022-12-13 at 12 13 54 PM" src="https://user-images.githubusercontent.com/50315486/207566853-7ec07647-22f0-4bd9-93a1-332ffab28659.png">

**Classification Report**
<img width="485" alt="Screenshot 2022-12-13 at 12 14 06 PM" src="https://user-images.githubusercontent.com/50315486/207566961-ed61db5a-76c2-41e0-b3c4-5abe007ea1be.png">



