# Disease-diagnosis
# Period diagnosis of soybean bacterial spot disease
This project introduces a method for the diagnosis of soybean bacterial spot disease based on the lack of data. This method can accurately identify the leaf diseases of soybean in different periods, meet the actual production needs, prevent the misuse of pesticides, and reduce the yield loss caused by soybean leaf diseases. It provides model theoretical support for intelligent diagnosis of soybean bacterial spot disease in different periods, which is of great significance for the prevention and treatment of bacterial spot disease, and has important reference value for other crop leaf disease diagnosis under missing data.

## environment
* CUDA 11.3
* cuDNN 8.2
* Pytorch 1.10.1
* Python 3.6
* Windows 10
# Training
Train a default Swin Transformer model with data on GPU:
```python
python train.py
``` 
# TEST
Model evaluation
```python
python eval.py 
```
# Predict 
```python
python Predict.py
```
# Data and Weights
The data and weights identified during the disease period can be obtained by opening the following Baidu website link:
