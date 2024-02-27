<img src="https://github.com/Faisal-1997/car_humane_detection/blob/master/img/air%20finder.png" alt="Watch the series" width="1000" height="180" border="10" />

### objective

#### our use cause is for searching for missing pepole in the desert or places hard to access, and send notification to the email when detecting the object inclouding the photo in the notification



### Data 
- we collection the data form Youtube and Splitting video into frames useing  CV2 lib and upload the images to  <a href="https://app.roboflow.com/faisalt5/airfinder/3" target="_blank">roboflow<a/> and label all images class annotation(car = 0 , person =1)
- Full dataset whit lables <a href="https://drive.google.com/drive/folders/1E6o3plOD4dk4FNviIkdF5clSspf9R3xM?usp=drive_link" target="_blank">drive link<a/>
- <a href="https://airfinderapp-eljtznrgk5mrdkhjaalzff.streamlit.app/" target="_blank">website<a/>


## Detection video
<a href="https://www.youtube.com/watch?v=-zF3a5BVEvc" target="_blank">
<img src="https://github.com/Faisal-1997/car_humane_detection/blob/master/img/airfinder20.png?raw=true" alt="Watch the series" width="240" height="180" border="10" />
</a>

### Model 
- by using Yolov8n we traind the model on custom dataset to detect pepole and cars using 250 epochs and save the best (class_loss=0.49 ,box_loss=0.64)
  
### deployment
- Install Raspberry Pi OS 
- Deploy the model on the raspberry pi 4  and Install it on the drone
  
<img src="https://github.com/Faisal-1997/car_humane_detection/blob/master/img/drone_1.jpg?raw=true" alt="Watch the series" width="240" height="180" border="10" />  <img src="https://github.com/Faisal-1997/car_humane_detection/blob/master/img/drone_2.jpg?raw=true" alt="Watch the series" width="240" height="180" border="10" />  <img src="https://github.com/Faisal-1997/car_humane_detection/blob/master/img/drone_3.jpg?raw=true" width="240" height="180" border="10" />


### result

## Lib
1. Ultralytics
2. Opencv




