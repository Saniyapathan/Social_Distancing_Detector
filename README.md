# SDD
## Social Distancing Detector   
This framework is for automating the task of monitoring social distancing using surveillance video. The proposed framework utilizes the YOLO object detection model to segregate humans from the background and approach to tracking the identified people with the help of bounding boxes. In the Social Distancing Detector I'll be using YOLO Object Detection Algorithm and the COCO dataset for which we are able to detect an individual in the real-time video stream. The main library being used will be the OpenCV along with the Deep Neural Network (DNN) module. The detector is able to detect if the crowd is following social distancing and marks the people who are not in safe distances with a red box and the safe people with a green box.



Here's the drive link to download whole code directory wth coco data set. (The above repository does not contains coco dataset.)

https://drive.google.com/drive/folders/1r8KCuuYWixf07HKS_Y6vT6Bl_njlDoro?usp=sharing    

The directory contains:
 
 
 
 
# Requirements

Install Opencv       
(Open Command Prompt)
pip install opencv-python

Install numpy   
pip install numpy   

Install coco-dataset (if not referred drvie link download)   
https://cocodataset.org/#home    




For output:

Open Command Prompt 
(Go to the directory using cd command )
python social_distance_detector.py --input pedestrians.mp4


Output:

