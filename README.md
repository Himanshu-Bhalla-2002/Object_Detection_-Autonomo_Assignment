<H1 align="center">
YOLOv8 Object Detection (Entering and Leaving) with DeepSORT Tracking </H1>

## Steps to run Code

- Clone the repository
```
git clone https://github.com/Himanshu-Bhalla-2002/Object_Detection_-Autonomo_Assignment
```
- Goto the cloned folder.
```
cd YOLOv8-DeepSORT-Object-Tracking
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```
- Downloading the DeepSORT Files From The Google Drive 
```

https://drive.google.com/drive/folders/1bWlTjms86q3eSlExPII4OpHwGQg1fg9t?usp=sharing
```
- After downloading the DeepSORT Zip file from the drive, unzip it go into the subfolders and place the deep_sort_pytorch folder into the yolo/v8/detect folder

- Downloading a Sample Video of your choice


- Run the code with mentioned command below.

- For yolov8 object detection + Tracking
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```
- For yolov8 object detection + Tracking + Vehicle Counting
- Download the updated predict.py file which I have submitted to you and place it into ultralytics/yolo/v8/detect folder 

- For yolov8 object detection + Tracking + Vehicle Counting
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```

### RESULTS

#### Vehicles Detection, Tracking and Counting 
![](https://i.imgur.com/5qflrh2.png)

#### Vehicles Detection, Tracking and Counting

![](https://i.imgur.com/zqBkch4.png)

