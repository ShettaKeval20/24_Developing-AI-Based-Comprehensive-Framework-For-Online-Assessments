# 24_Developing-AI-Based-Comprehensive-Framework-For-Online-Assessments

# Group Members 
 1) Swapnil Sapre
 2) Kunal Shinde
 3) Keval Shetta


# Description

1) Web based proctoring application that has 2 working ends:
   i) Student End 
   ii) Teacher End

2) Features
   a) Teacher's End
      
      i) Create Exam by importing document, View/Add/Update Questions.
      
      ii) Check Student real time logs.
      
   b) Student's End
      
      i) Attempt the exam
      
      ii) Capture images from live environment and analyze it.
      
   c) Proctoring Mechanism
        
        i) Detection of mobile.
        
        ii) Person detections in terms of: 
            
            a) no person detected
            
            b) multiple persons detected
        
        iii) Tab Switching activity and terminate the exam after 5 attempts.
   
3) Technology Stack used
   i) HTML , CSS , Bootstrap
   
   ii) DeepFace : for face detection and validation purposes
   
   iii) YOLO weights : for object detection
   
   iv) Flask - Python : framework for developing web application in python

# Complete Code Link
https://drive.google.com/drive/u/1/folders/1urSFYKU51PlRjbDwS9F8mHuJ8Zs2ZbOU

# Files Required
Variables file : https://www.mediafire.com/file/bp4stjan6z77h9b/variables.data-00000-of-00001/file

Variables Index file : https://www.mediafire.com/file/n4m90dmwtvumpfs/variables.index/file

Yolo file : https://www.mediafire.com/file/hd2sfcxicgy4vll/yolov3.weights/file

# Commands and Execution
Create Environment
1) download projectenv.yml from github

2) on anaconda terminal 
   
   2a) conda env create --name testenv --file=project_env.yml

1) open Xampp . Turn On apache & mysql

2) On anaconda terminal  
     
     2a) cd Desktop
     
     2b) cd foldername
     
     2c) activate testenv
     
     2d) python app.py
