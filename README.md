Forked from https://github.com/WongKinYiu/yolov7

A repository with YOLOv7 model trained to detect plants on the field. Sutable for photos and videos of plants taken from drones. <br>
Training dataset photo examples: <br>
![image](https://github.com/alexxandra-u/yolov7_for_plant_detection/assets/90149266/f5343fe5-161b-4b11-ac75-5e626f1d059a)


Download the model weights best.pt from here: 
https://drive.google.com/file/d/1GDaA7JDKkTUORxZCDde5PlbpfHvlaHQB/view?usp=sharing

Run detection on your picture with the command
```
!python detect.py --weights best.pt --conf 0.5 --img-size 640 --source picture_name.jpeg
```
