# Raspberry Pi IOT Project
### What is this Project
Using Raspberry Pi and Webcam
webcam is get the realtime video and use tensorflow capture the object
if specify object is exist (like person and bed)
check the person lie down bed
if true specify function run (ex : turn off light)

##
### Environment
Device : RaspberryPi4 4gb
OS : Rasbian 64bit
Webcam : Using DroidCam (Galaxy S3)
##
### How to Run
1. cd your Project Folder
2. source source (Project Folder name)-env/bin/activate
3. connect your Webcam
4. python3 p4_object_webcam.py --modeldir='Model Folder name'
5. Enjoy
##
### Reference
Tensorflow Lite on Android and RaspberryPi :https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi
