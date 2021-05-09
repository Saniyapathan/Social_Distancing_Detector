# SDD
## Social Distancing Detector   
This framework is for automating the task of monitoring social distancing using surveillance video. The proposed framework utilizes the YOLO object detection model to segregate humans from the background and approach to tracking the identified people with the help of bounding boxes. In the Social Distancing Detector I'll be using YOLO Object Detection Algorithm and the COCO dataset for which we are able to detect an individual in the real-time video stream. The main library being used will be the OpenCV along with the Deep Neural Network (DNN) module. The detector is able to detect if the crowd is following social distancing and marks the people who are not in safe distances with a red box and the safe people with a green box.



Here's the drive link to download whole code directory wth coco data set. (The above repository does not contains coco dataset.)   


https://drive.google.com/drive/folders/1r8KCuuYWixf07HKS_Y6vT6Bl_njlDoro?usp=sharing    

The directory contains:   

![Directory_SDD](https://user-images.githubusercontent.com/54326148/102059225-98e0bd00-3e16-11eb-96f9-b65a618b7e40.JPG)




 
 
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



![D](https://user-images.githubusercontent.com/5432618/102059370-d5141d80-3e16-11eb-9590-ec58bd0a3d15.JPG)






#DEMONSTRATION
 
 
 INPUT
 
 ![input video](https://user-images.githubusercontent.com/54326148/102059643-2c19f280-3e17-11eb-8efc-3deb323b1792.JPG)   
  
  
  OUTPUT  
  
  ![A](https://user-images.githubusercontent.com/54326148/102059812-6be0da00-3e17-11eb-82e1-d82a9290e275.JPG)    
  
  
  ![B](https://user-images.githubusercontent.com/54326148/102059867-7e5b1380-3e17-11eb-8bbf-94d3a7e205e9.JPG)





Social Benefits:

●	Control the spread of contagious diseases like covid19.
●	Ability to see which area gains the most traction .
●	Can be used in offices , schools , factories , etc. to monitor the working environment.

Conclusion

▪	This system can be used in CCTV for surveillance of people during pandemics. 
▪	Mass screening is possible and hence can be used in crowded places .
▪	By monitoring the distance, maintaining social distancing in the right way will enable us to curb the virus.
