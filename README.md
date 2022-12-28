# yolov5_object-_detection_and-_blur

# yolov7-object-blurring

-clone repo

- Create a virtual envirnoment (Recommended, If you dont want to disturb python packages)

- Upgrade pip with mentioned command below.
```
pip install --upgrade pip
```
- Install requirements with mentioned command below.
```
pip install -r requirements.txt
```

#if you want to change source file
python detect_and_blur.py --weights yolov7.pt --source "input" --blurratio 20

#for specific class (person)
python detect_and_blur.py --weights yolov7.pt --source "input" --classes 0 --blurratio 50

#hide-detected-bounding-boxes
python detect_and_blur.py --weights yolov7.pt --source "input" --classes 0 --blurratio 50 --hidedetarea



