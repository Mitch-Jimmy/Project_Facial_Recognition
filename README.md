# Project_Facial_Recognition

Project Facial Recognition is my first personal project using Nvidia Jetson Nano. Building a good foundation, I started by recognizing facial features in frames, a basic function that will also be used in upcoming projects. 
This project implements a real-time edge detection system using a USB webcam and an Nvidia Jetson Nano. The webcam first captures frames containing our faces. Each pixel will be converted to grayscale and processed using the five stages of the Canny edge detection algorithm. Regions with rapid density change correspond to the boundaries of our object. This measurement provides a lightweight method for detecting visual structures and motions without performing heavy calculations for full object recognition and without the need for high-end machines.
Using the Canny algorithm, this approach forms a foundation for more advanced computer-vision tasks such as face-tracking, biomedical monitoring, and autonomous systems.
