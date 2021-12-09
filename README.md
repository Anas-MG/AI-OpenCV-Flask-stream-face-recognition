 ### Real Time video stream with face Detection & Recognition 
##### The is a simple project to learn how to create a live stream detection & recognition for the robot's cam 
#
#### Environment:
##### Python 3, Opencv 4
![ScreenShot_stream](https://user-images.githubusercontent.com/49666154/124705190-40acfd80-dec3-11eb-8d7d-ae8f4b83310c.png)
##### The project built using HTML, JavaScript, Python's flask for live streaming, Opencv to detect and recognize faces. 
###### It containts python3 script that serves Flask video webserver that allows to take photos or see real time video streaming of a connected camera/webcam with OpenCV detection & recognition.

- #### pre requirements : 
 ````
 $ pip3 install flask 
 $ pip3 install opencv-python
 $ pip3 install face_recognition 
 ````
#### Run:
````
$ cd ~/project_folder 
$ python server.py 
or
$ python3 server.py 
````
It only runs on python3
after This step is done navigate to the ip of the server and access the port 5000.
`` http://localhost:5000 ``

##### The project was originally for live stream detection cloned from "https://github.com/ramonus/flask-video-stream"
#


