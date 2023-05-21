### This is Garbage Detection Algorithm

```
Following preprocessing and post processing steps are implemented:

1. YOLOV5
2. Preprocessing custom dataset
	1. Extracting Bounding box coordinates from images
	2. Preparation of train, test ,validation images
3. Training on custom dataset
4. Testing on custom dataset
5. Converting yolov5s.pt to onnx
	Validating yolov5.onnx
6. Converting yolov5.onns to tensorrt  engine
	Validating yolov5 engine 
7. Make an inference on Garbage dataset with yolov5 engine model

Detections are done on following 6 objects:

1. Trash
2. Plastic
3. Cardboard
4. Card
5. Glass
6. Others
```
