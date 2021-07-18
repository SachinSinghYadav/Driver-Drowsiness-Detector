


This program is used to detect drowsiness for any given person. In this program we check how long a person's eyes have been closed for. If the eyes have been closed for a long period i.e. beyond a certain threshold value, the program will alert the user by playing an alarm sound.

The program contains 3 files, which are
## Files
 -

 - **face_and_eye_detector_webcam_video.py** - Detects face and eye in a webcam feed by user![Webcam Face and Eye Detection](https://github.com/SachinSinghYadav/Driver-Drowsiness-Detector/blob/master/images/Face_and_Eye.png)
 - **drowsiness_detect.py**- This script detects if person is drowsy or not using webcam video feed

> DEMO
![Drowsiness Detection Demo](https://github.com/SachinSinghYadav/Driver-Drowsiness-Detector/blob/master/images/Drowsiness_demo.png)
 
 ## Requirements
> 
> IMPORTANT

  Download `shape_predictor_68_face_landmarks.dat.bz2` from [Shape Predictor 68 features](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) 
  Extract the file in the project folder using 
  ``bzip2 -dk shape_predictor_68_face_landmarks.dat.bz2``


    numpy==1.15.2
	dlib==19.16.0
	pygame==1.9.4
	imutils==0.5.1
	opencv_python==3.4.3.18
	scipy==1.1.0
Use `pip install -r requirements.txt`to install the given requirements.

## Usage

### Detect Face and Eyes in a Webcam Feed
Run script using:

    python face_and_eye_detector_webcam_video.py
### Drowsiness Detection
Run script using:

    python drowsiness_detect.py

