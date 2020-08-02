# OIDv4_Toolkit-Custom-Dataset-Collector

Open Images is a dataset of ~9M images annotated with image-level labels, object bounding boxes, object segmentation masks, visual relationships, and localized narratives. Download Your own dataset by entering the given commands in CMD or Anaconda Prompt

Step1)-- Check for your convinient dataset on https://storage.googleapis.com/openimages/web/visualizer/index.html?set=train&type=detection&c=%2Fm%2F044r5d

Step2)-- Go to--> Type--> Select Detection

Step3)-- Go to--> Options --> Deselect-- Display Boxes from all Catagory

Step4)-- Make Sure to input the same class you Searched after "--classes" in the COMMAND BELOW

Step5)-- Mention the command --limit and the number of images for each class

Step6)-- Modify Below command accordingly and Run in the directory of "OIDV4_Toolkit" where "main.py" is present

Step7)-- Type "Y" If asked for the permission
        "python main.py downloader --classes Frying_Pan Refrigerator --type_csv train --limit 200 "
        
Step8)-- After the download your dataset of Yolo wiil be present in OIDv4_Toolkit-Custom-Dataset-Collector-->OID-->Dataset-->train

Step9)-- In the downloaded repository you will get "classes.txt" Modify that with your own classes //ONE CLASS PER LINE

Step10)-- Run python "convert_annotations.py"

Your CUSTOM YOLO DATASET IS READY

Refered from the video on Youtube Reference: https://www.youtube.com/watch?v=_4A9inxGqRM
