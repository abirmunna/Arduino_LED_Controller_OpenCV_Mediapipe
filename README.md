# Arduino_LED_Controller_OpenCV_Mediapipe
---
---
**Steps:**

 1. Download  and install [Miniconda](https://conda.io/en/latest/miniconda.html?highlight=conda).
 2. Open Anaconda prompt. (press windows key and search for anaconda prompt)
 3.  Run commands to install necessary packages:

>     pip install opencv-python
>     pip install opencv-contrib-python
>     pip install pyFirmata
>     pip install mediapipe

4. Connect the Arduino board and upload the StandardFirmata sketch using arduino ide. You can follow this [tutorial](https://www.youtube.com/watch?v=2L8YYJpfuvE).
5. Get the COM port of the Arduino board by opening device manager.
6. Write the COM port in the [controller.py](https://github.com/abirmunna/Arduino_LED_Controller_OpenCV_Mediapipe/blob/main/controller.py) file's comport section `comport='COM11'`
7. Run the [main.py](https://github.com/abirmunna/Arduino_LED_Controller_OpenCV_Mediapipe/blob/main/main.py) file and control led's using finger detection. 
		 
