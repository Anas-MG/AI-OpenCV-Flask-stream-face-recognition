 ### Real Time video stream with face Detection & Recognition 
##### The is a simple project that creates a live stream with OpenCV detection & recognition. 
##### The idea is to learn how to make the Robot's cam smarter.
#
#### Environment:
##### UBUNTU 20.04, Python 3, Opencv 4.
![ScreenShot_stream](https://user-images.githubusercontent.com/49666154/124705190-40acfd80-dec3-11eb-8d7d-ae8f4b83310c.png)
##### The project built using HTML, JavaScript, Python's flask for live streaming, Opencv to detect and recognize faces. 
###### It containts python3 script that serves Flask video webserver that allows to take photos or see real time video streaming of a connected camera/webcam with OpenCV detection & recognition.

- ### Pre requirements : 
 ````
 $ pip3 install flask 
 $ pip3 install opencv-python
 $ pip3 install face_recognition 
 ````
 #
### Run:
````
$ cd ~/project_folder 
$ python server.py 
or
$ python3 server.py 
````
##### It only runs on python3, after This step navigate to the ip of the server and access the port 5000.
`` http://localhost:5000 ``
#
#### Files: 
- ###### html pages and JavaScript
> ###### Folder: templates
- ###### configurations script 
> ###### file: conf.py
- ###### Flask stream script 
> ###### file: stream.py
- ###### capture and OpenCV scripts
> ###### files: capture.py camera.py


