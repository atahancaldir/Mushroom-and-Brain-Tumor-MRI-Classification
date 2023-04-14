

# Brain Tumor MRI & Mushroom Classifications

"CS 454 - Introduction to Machine Learning and Artificial Neural Networks" course project.

> Datasets should be downloaded externally from the given links due to storage problems. For both classification tasks, code are explained in detail inside the .ipynb files.

### **Brain Tumor MRI Classification**

Comparison of two different brain tumor MRI classification methods using VGG16 CNN model;

**Case 1:** VGG16 model is trained with the original image
**Case 2:** Images are passed to the Auto Encoder first, and then VGG16 model is fed with the output of the Auto Encoder

Results showed that the accuracy was increased from around 92% to around 97%, and also the training time of the VGG16 model has decreased to half when the Auto Encoder is used.

Dataset:[ Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

### Mushroom Classification

Detailed mushroom dataset analysis and classification by comparing the performances of three different algorithms:

1. K-Nearest Neighbors (KNN)
2. Support Vector Machine (SVM)
3. Random Forest

Results are explained and visualized using confusion matrices.

Dataset: [UCI Machine Learning Repository - Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/mushroom)
