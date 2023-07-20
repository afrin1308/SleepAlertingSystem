
# Sleep Alerting System

A brief description of what this project does and who it's for

On average 1200 rest gets effected badly. The major reason of 
these accidents is drowsiness caused by both sleep and alcohol. 
Due to driving for long time or intoxication, drivers might feel 
sleepy which is the biggest distraction for them while driving. 
This distraction might cost death of driver and other passengers 
in the vehicle and at the same time it also causes death of people
in the other vehicles and pedestrians too. This mistake of one 
person on road would take their own life and also takes lives of 
other and put respective families in sorrow and tough situations. 
To prevent such accidents we, team 5A propose a system which 
alerts the driver if he/she feels drowsy. To accomplish this, 
we implement the solution using computer-vision based machine 
learning model. The driver’s face is detected by face recognition 
algorithm continuously using a camera and the face of the driver 
is captured. The face of the driver is given as input to a 
classification algorithm which is trained with a data set of 
images of drowsy and non-drowsy faces. The algorithm uses 
landmark detection to classify the face as drowsy or not drowsy. 
## Deployment

To deploy this project in Visual Studio terminal run

```cmd
```py sas.py runserver


## Demo

Insert gif or link to demo


## Documentation

[Documentation](https://docs.google.com/document/d/1h4xaQVIWYazuQZEWoHfax_16vwyqhEoP/edit)

The Documentation is available 
## Usage/Examples

```Python
```Detect Face and Eyes in a Single Image
Put your file to be detected in images folder with name test.jpeg or change the file path in Line : 14 face_and_eye_detector_single_image.py to your image file.
Run script using:

python face_and_eye_detector_single_image.py
Detect Face and Eyes in a Webcam Feed
Run script using:

python face_and_eye_detector_webcam_video.py
Drowsiness Detection
Run script in Visual Studio using:

py sas.py runserver



## 🔗 Links
https://github.com/settings/profile (github profile link)

## Screenshots


![Alt text](https://drive.google.com/drive/folders/1RTAXDhdB9oIKWRiyjmfuLuoYmOxkpIKm
 "Screenshots")
## Roadmap

The Requirements for this project are
numpy==1.15.2
dlib==19.16.0
pygame==1.9.4
imutils==0.5.1
opencv_python==3.4.3.18
scipy==1.1.0

Install the Requirements in command prompt or windows power
shell by using the command:
    python -m pip install PackageName==VersionNumber --user
## Support

For support, email neenunaz2002@gmail.com 
or contact sushuramya2422@gmail.com
           sk.afrin42@gmail.com
           bhargaviemani15@gmail.com 


## Authors

The algorithm for Eye Aspect Ratio was taken from 
pyimagesearch.com blog, by Adrian RoseBrock.

