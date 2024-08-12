# Object-Detection
This project was developed during a hackathon at RGMCET by BYTS INDIA(BYTS HACKLEAGUE 1.0) within a 24-hour timeframe.
# Project Description
The Object-detection project is aimed at automatically detecting the objects and managing the count.It uses computer vision techniques to detect the individual objects and gives the count of individual object.The project includes a user-friendly dashboard for monitoring and an interactive tool for detecting the objects.The project aims to provide the following functionality:
# Object Detector
The object detector component utilizes computer vision techniques to identify individual objects in a given video frame.It also detect the objects in live based camera using image processing algorithms.It provides accurate information about objects.
# Features
* Real-time monitoring of detecting and counting of individual objects
* Display of available objects and display the count
# Codes
* main.py : This code is used to detect the objects using live camera
* tracker.py : This code is used to track the objects and this is imported in main.py
* main2.py : This code is used to access the live cctv footage and detect the objects.
# Usage
Download the Thonny python IDE.
Install Thonny python IDE.
Run main.py for detecting and counting the objects using live camera.
Run main2.py for detecting and specifying the count of an individual object using live cctv footage.
# Project Dependencies and Installation
 For running main.py:
   Open Thonny python IDE  :
   Open Tools tab ----> Manage packages
* We will get packages window 
* Now Install the below mentioned packages
* opencv-python version -4.7.0.68
* yolov5

 For running main2.py:
   open Tools tab ----> Manage packages
* We will get packages window 
* Now Install the below mentioned packages
* opencv-python version -4.7.0.68
* tensorflow
* cvlib ---> for object detection
* videogear --->for accessing live video
* vidgear ---> for accessing live video
* yt-dlp ---> To access live cctv footage from youtube
