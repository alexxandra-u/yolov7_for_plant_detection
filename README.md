Forked from https://github.com/WongKinYiu/yolov7

A repository with YOLOv7 model trained to detect plants on the field. Sutable for photos and videos of plants taken from UAV. <br>
Trained on dataset https://datasetninja.com/plant-detection-and-counting <br>
Photo examples: <br>
![image](https://github.com/alexxandra-u/yolov7_for_plant_detection/assets/90149266/f5343fe5-161b-4b11-ac75-5e626f1d059a)

Training code available in "YOLOv7_training.ipynb"
Code of dataset transformation and augmentation available in "dataset_transform_and_augmentation.ipynb"


**Usage**:

Clone this repository

Download the model weights "best.pt" from here: 
https://drive.google.com/file/d/1GDaA7JDKkTUORxZCDde5PlbpfHvlaHQB/view?usp=sharing

Put the weights in the main repository folder

Put your picture or video in "test_pictures" folder

Run detection with the command
```
!python detect.py --weights best.pt --conf 0.2 --img-size 640 --source test_pictures/picture_name.jpeg
```

If a bad result occurs try changing the conf value