<H1 align="center">
YOLOv8 Object Detection with DeepSORT Tracking </H1>


## Steps to run Code


```
cd YOLOv8-DeepSORT-Object-Tracking-main
```
- Install the dependecies
```
pip install -e '.[dev]'

```

- Setting the Directory.
```
cd ultralytics/yolo/v8/detect

```

- Run the code with mentioned command below.

- For yolov8 object detection + Tracking
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```

```
- For yolov8 object detection + Tracking + Vehicle Counting
```
python predict.py model=yolov8l.pt source="test3.mp4" show=True
```
- For faster execution
```
python predict.py model=yolov8n.pt source="test3.mp4" show=True
``
