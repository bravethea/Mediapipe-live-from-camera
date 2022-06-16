# MediaPipe live from camera

Runs ```mediapipe``` with body and face detection live from camera.

In order to install ```mediapipe```, ```python 3.7``` is required. 

## Prerequisites
### Virtual environment

You can set up a virtual environment from the terminal with ```python 3.7``` by running

```python3.7 -m venv mp_env``` 

and activate it by running

````source mp_env/bin/activate    ````

### requirements.txt

the project has the following requirements (see ```requirements.txt```):

```
mediapipe
absl-py
attrs>=19.1.0
matplotlib
numpy
opencv-contrib-python
protobuf>=3.11.4
```

You can install the required packages by running 

```pip install -r requirements.txt```

## Camera detection

You can run the program from the terminal by running 

```python3 mediapipe_live_from_camera.py```.

That opens a new window with a live camera stream, and a pose estimation overlay for the main person in the frame.

Once the program is running, you can quit it by pressing ```q``` while running in the terminal.

