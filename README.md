# Digit Classification

By Beverly Huang

### Goal
Image data is an interesting data type to explore with Python. By applying the classification technics of machine learning, this project will use two models to classify written digits based on image data. These two models will be evaluated and benchmarked to understand the processing of image data.

### Conclusion
The project aims to classify written digits based on image data. Two models are used in this project. SVC model classifies digits based on "images" attribute of the dataset (which is an 8*8 image), while logistics regression model uses "data" attribute of the dataset (which is a single array of features about the 64 pixels). We evaluate the accuracy of two models using classification report, confusion matrix, ROC curve. The result shows that the SVC model has higher accuracy in classification. One explanation might be that the 8*8 image data contains richer information than the features about 64 pixels, thus the model using 8*8 image data performs better in classification.
