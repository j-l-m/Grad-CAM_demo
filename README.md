# Grad-CAM_demo
Part of MSc project. Involves using Grad-CAM to visualize which regions of an image were important for classification


A **jupyter notebook** displaying a use of **Grad-CAM** to highlight areas of an image that were important for a prediction.

This technique was used with VGG16 and MobileNet to help interpret the performance of the CNNs.It helps to show how the models were making predictions. CNNs may learn unexpected features from the images in the dataset e.g. areas of the background rather than the subject of the image.

The example uploaded here uses VGG16.


Grad-CAM paper: 
Selvaraju, Ramprasaath R., Michael Cogswell, Abhishek Das, Ramakrishna Vedantam, Devi Parikh, and Dhruv Batra. 2019. *“Grad-CAM: Visual Explanations from Deep Networks via Gradient-Based Localization.”* International Journal of Computer Vision, October. https://doi.org/10.1007/s11263-019-01228-7.


The solution in this notebook is based on the implementations by:
* F. Chollet(2017) in his *Deep Learning with Python* book
* Rapahel Meudec's, writer of the tf-explain library, solution which is updated for TensorFlow 2.0: [source](https://stackoverflow.com/questions/58322147/how-to-generate-cnn-heatmaps-using-built-in-keras-in-tf2-0-tf-keras)


**Example of Grad-CAM-output given below**
![Grad-CAM output](/sample.jpg?raw=true)
