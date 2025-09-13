# YOLOv8-Object-Detection-with-DeepSORT-Tracking


### Features
YOLOv8 Object Detection with DeepSORT Tracking(ID + Trails)


### Steps to run Code

- Clone the repository
```
git clone https://github.com/noorkhokhar99/YOLOv8-Object-Detection-with-DeepSORT-Tracking.git
```

- Goto cloned folder
```
cd YOLOv8-Object-Detection-with-DeepSORT-Tracking
```

- Install the ultralytics package
```
pip install ultralytics==8.0.0
```

- Setting the Directory.
```
cd yolo/v8/detect
```
- Copy deep_sort_pytorch folder and place the deep_sort_pytorch folder into the yolo/v8/detect folder



- Do Tracking with mentioned command below
```
# video file
python tracking_vehicle_counting.py model=yolov8l.pt source="test.mp4" show=True
```




### Results
<table>
  <tr>
    <td>YOLOv8-Object-Detection-with-DeepSORT-Tracking</td>
  </tr>
  <tr>
    <td><img src="https://github.com/noorkhokhar99/YOLOv8-Object-Detection-with-DeepSORT-Tracking/blob/main/Screen%20Shot%202023-01-16%20at%202.15.57%20pm.png"></td>
  </tr>
 </table>



This project is based on YOLOv8-Object-Detection-with-DeepSORT-Tracking by MuhammadMoinFaisal.
I've fixed compatibility issues and improved the codebase for modern PyTorch versions.
What I Fixed/Improved:

- Fixed PyTorch 2.8+ compatibility issues - Resolved weights_only parameter conflicts
- Resolved torch.load weights_only parameter conflicts - Added proper parameter handling
- Updated deprecated package warnings - Fixed pkg_resources deprecation warnings
- Added proper error handling - Improved user experience with better error messages
- Environment compatibility - Ensured compatibility with Python 3.13 and latest dependencies
- Documentation improvements - Added clear setup and troubleshooting instructions
