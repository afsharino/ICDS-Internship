# E-commerce Product Image Classification
<<<<<<< HEAD
</br>
=======

</br>

>>>>>>> fb461d1b4ac533a466de43db552bc663492c4419
## Table of contents
- [Introduction](#Introduction)
- [Dataset](#Dataset)
- [Model Architecture](#Model-Architecture)
- [Training and Evaluation](#Training-and-Evaluation)
- [Usage](#Usage)
- [Results](#Results)
- [Conclusion](#Conclusion)

---

## Introduction
This project focuses on developing a convolutional neural network (CNN) model to classify images of products from an e-commerce website. The goal is to determine whether the image contains a laptop or a mobile phone.

---

## Dataset
The dataset used in this project was collected from [esam](https://esam.ir/ "esam") during the data collection phase. The images were manually selected and cleaned to ensure high-quality data for training and evaluation.

Please note that due to the nature of the dataset and privacy concerns, the dataset is not included in this repository. However, you can collect similar images from [esam](https://esam.ir/ "esam") or any other relevant sources to train and test the model.

---

## Model Architecture
The implemented model follows a CNN architecture, inspired by VGG networks. It consists of convolutional layers, pooling layers, flatten layers, dense layers, dropout layers, and an output layer. The number of parameters in the model is approximately 1 million, considering the complexity of the image patterns.

Data augmentation techniques, such as rotation, zooming, shifting, and flipping, have been applied using the ImageDataGenerator class from TensorFlow's Keras API. This helps to increase the variety and size of the training data and improve the model's generalization.

---

## Training and Evaluation
The dataset was split into training and testing sets using a 75:25 ratio. The model was trained on the training data using the Adam optimizer and binary cross-entropy loss. During training, the accuracy and loss were monitored and plotted for both the training and validation sets.

Additionally, transfer learning was employed by utilizing the pre-trained VGG16 model. The base model was loaded and frozen, and new layers were added on top to fine-tune the model. This approach allowed leveraging the knowledge gained from the pre-trained model while adapting it to the specific product image classification task.

---

## Usage
To use this code, follow the steps below:

1. Collect a dataset of product images from esam.ir or other relevant sources.

2. Organize the dataset into two folders: "laptop" and "mobile" based on the product category.

3. Update the file path in the ```read``` function to point to the directory containing the dataset.

4. Adjust the image size and other parameters in the code as needed.

5. Run the code to train the model and evaluate its performance.

6. To make predictions on new images, utilize the ```read_samples``` and ```predict``` functions provided.

Feel free to modify the code and experiment with different model architectures, hyperparameters, and optimization techniques to further enhance the performance.

---

## Results
The accuracy of the model on the test set achieved significant improvements during the training process, reaching a satisfactory level for the given task. The model was able to semi-accurately classify product images as either laptops or mobile phones.

To visualize the model's predictions, the ```predict``` function can be used on new test images. The function plots the input images alongside the predicted class labels.

---

## Conclusion
This project demonstrates the application of CNNs for e-commerce product image classification. By training a model on a dataset collected from [esam](https://esam.ir/ "esam"), the model successfully identifies laptops and mobile phones in product images. The use of data augmentation and transfer learning techniques further improves the model's performance.

Please note that this project serves as an example and a starting point for further exploration. Additional improvements can be made by experimenting with different architectures, hyperparameters, and optimization strategies.

Feel free to reach out for any questions or suggestions
<<<<<<< HEAD

---
## Acknowledgements
I would like to express my sincere gratitude to the following individuals and organizations for their contributions and support throughout this project:

- ***Mahdi Nasehiyan***: Special Thanks to my dear friend [Mahdi](https://github.com/iminsightman "mahdi-github"). for providing guidance, expertise, and valuable feedback during the internship. Your insights have been instrumental in the development of this project.

- ***ICDS***: I would like to thank the [ICDS](https://icds.ai/ "icds-websitr") company for organizing the internship program and providing the opportunity to work on real-world projects and gain experience.

Lastly, I would like to extend my thanks to the readers of this README file. Your interest and engagement are greatly appreciated. If you have any questions, suggestions or feedback, please feel free to [reach out](https://t.me/afsharino "afsharino-telegram").

made with love by [afsharino](https://github.com/afsharino "afsharino") & [ChatGPT](https://chat.openai.com/ "ChatGPT") :purple_heart:
=======
>>>>>>> fb461d1b4ac533a466de43db552bc663492c4419
