# ANPR-Using-TensorFlow-Pytorch
This project aims to implement basic ANPR(Automatic Number Plate Recognition system) using OpenCV and Easyocr (PyTorch) in Python. The program extracts the number plate information from a picture or a static videoframe and stores it in CSV file with date of entry.

# What is ANPR ?
Automatic number-plate recognition is a technology that uses optical character recognition on images to read vehicle registration plates to create vehicle location data. It can use existing closed-circuit television, road-rule enforcement cameras, or cameras specifically designed for the task. ANPR is an advanced version of what I am going to show you in this article. Here, we will be implementing the software part. The hardware part can be implemented using CCTV cameras and Raspberry Pi.

# Steps involved :
1. Setup Tensorflow API.

2. Download Pretrained model.

3. Download Dataset from kaggle. 

https://www.kaggle.com/andrewmvd/car-plate-detection

4. Train data using Tensorflow model weights

5. Read no plate using object detection.

6. Read the text using Easyocr.

7. Real time Car No. Plate Recognization

8. Detected file store in a csv format.
