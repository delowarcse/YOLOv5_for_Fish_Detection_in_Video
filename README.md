# YOLOv5 for Fish Detection in Video

Please follows all the instruction from the YOLOv5 repository: https://github.com/ultralytics/yolov5. Then, copy the pre-trained fish weight (yolov5n_model.pt) in the pretained weight path and fish detection script (fish_detect_fish.py) in the main folder.

##### After then follow the following instructions:
1.	Please use your terminal to navigate the yolov5 folder
2.	Run: 
```
$ python fish_detect_delowar.py --weights path_to_pretrained_weight/yolov5n_model.pt --source the_path_to_the_video_file/cam-2_20220428074001.mp4 --save-txt
```
3.	Output will save to the …../yolov5/runs/detect/

## If you want to perform the following task:
1. Extract images/frames from video.
2. Pass the images/frames through the YOLOv5 model (load the model with the weights provided).
3. Extract the bounding box coordinates for each frame of the video and write them to a text file. For example, the video has 600 frames in it, so, the txt file should have 600 lines with each line containing the detections. In other words, each line should be a list with bounding box coordinates or a list of bounding box coordinates if there are multiple detections in a frame.

##### Please run the following script:
- Run:
```
$ python detect_fish_delowar.py --weights path_to_pretrained_weight/yolov5n_model.pt --source the_path_to_the_video_file/cam-2_20220428074001.mp4 --save-txt
```
- Output will save to the …../yolov5/runs/detect/
