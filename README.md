# MediaPipe live from camera

Runs ```mediapipe``` with body and face detection live from camera.

In order to install ```mediapipe```, ```python 3.7``` is required. 

You can set up a virtual environment by running

```python3.7 -m venv mp_env``` 

in the terminal.
Also see ```requirements.txt```.

You can run the program from the terminal by running 

```python3 mediapipe_live_from_camera.py```.


That opens a new window with a live camera stream, and a pose estimation overlay for the main person in the frame.

Once the program is running, you can quit it by pressing ```q``` while running in the terminal.