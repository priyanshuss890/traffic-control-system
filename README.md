# Traffic-Control-System
Current system for traffic control leads to wastage of time and fuel and which in turn causes frustration and money-loss.So to tackle the problem, the proposed system is implemented in MATLAB with an objective to reduce the traffic based on density. This project is based in Computer Vision using Blob Analysis for vehicle detection and counting them to get density of each lane. A camera is installed and used to capture video of the highway. The video is recorded continuously in consecutive frames and frame is processed after each iteration completed. There are predefined some frames for detecting background. The total number of cars present in the video is found out using computer vision algorithms. 

>Hardware Module: A USB based web camera to record video of the traffic on road. The hardware module consists of an Arduino board used to control LEDs representing the red and green lights. A timer module is used to display the remaining time.

>Software Module: MATLAB version R2021a is used as the software which comprises specialized modules and tools like Computer Vision Toolbox and Image Processing Toolbox that perform specific tasks. And for better experience app is designed using App Designer inbuilt in MATLAB.

>Interfacing: A webcam is interfaced to the system and and that is interfaced to MATLAB.

# Future Work
The weather conditions are not taken into account which may affect the frame quality when it becomes foggy or in heavy rains. And should have night vision cameras for working in night smoothly. More advancements can be made to the proposed system to check identification of vehicles that pass through the system circle which could help in traffic surveillance.
