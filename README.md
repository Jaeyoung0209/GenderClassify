# Tensorflow Gender Classification Model

A real-time gender classifier built on google colab. Dataset was obtained from a public upload on Kaggle.

There are two parts to this project:
* Human face detection
* Gender classification for detected faces

The first part is done using a built-in function from the cv2 library, but the classification part was done by training an image classification model in Keras. Reached a final accuracy of around 95% on the testing dataset.

![Genderipynb-Colaboratory-Google](https://github.com/Jaeyoung0209/GenderClassify/assets/112497692/10a3b0ca-a7c0-4e9a-bb26-c48573a8ffbd)

Shows the classifier running on multiple people at once through a webcam. The detection box tracks all faces on the screen, feeds each of them through the trained model, and returns its output as a label above the box.

![Gender ipynb - Colaboratory - Google Chrome 2024-01-16 20-34-17 - Trim (1) (1) (1) (1)](https://github.com/Jaeyoung0209/GenderClassify/assets/112497692/49b6c673-a72d-41c4-b8e9-5b9110ca6191)


This is an example of the model detecting a male and a female face at the same time.
