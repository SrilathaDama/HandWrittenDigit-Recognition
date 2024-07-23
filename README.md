# Handwritten Digit Recognition

## Project Overview
This project focuses on the recognition of handwritten digits using machine learning techniques. The primary goal is to classify images of handwritten digits (0-9) from the MNIST dataset. The notebook provided demonstrates the process of training a machine learning model to achieve high accuracy in digit recognition.

## Dataset
- **Source**: MNIST dataset
- **Content**: 70,000 grayscale images of handwritten digits (28x28 pixels)

## Methodology
1. **Data Preprocessing**
   - Normalization of pixel values
   - Reshaping of data for model compatibility

2. **Model Building**
   - Utilization of Convolutional Neural Networks (CNN)
   - Layer configuration:
     - Convolutional layers
     - Max-pooling layers
     - Dense (Fully Connected) layers
   - Activation functions: ReLU, Softmax

3. **Training and Evaluation**
   - Model compilation with loss function and optimizer
   - Training the model on training data
   - Evaluation on test data to measure accuracy and performance

## Results
The trained model achieves a high accuracy rate on the test dataset, showcasing the effectiveness of the CNN architecture for handwritten digit recognition tasks.

## Requirements
- Python
- Jupyter Notebook
- Libraries: TensorFlow, Keras, NumPy, Matplotlib

## Conclusion
This project demonstrates an effective approach to recognizing handwritten digits using deep learning. The CNN model provides accurate classification, making it suitable for applications requiring digit recognition.

## Author
[Srilatha Dama](https://github.com/SrilathaDama)

For more details, check the [project repository](https://github.com/SrilathaDama/HandWrittenDigit-Recognition).
