# Gesturerecognization
There may occur a situation where there is sudden requirement of camera and that moment  is so  instant that there is not enough time to open camera or any other capturing device.This is the point where Raspberry Pi comes handy as it is a IoT device it can be turned on or off anytime.A specific gesture can be set through which image can be clicked by any capture device in our case it is Android Camera connected to Raspberry Pi by online server . 



#How to use:

There is url given in code named "Gesture.py" is from the image address.

Now how to get Image Address?.
So now we have to connect our project or Raspberry Pi with our android camera

Step 1:  Download IP2WEBCAM 
         Link :https://play.google.com/store/apps/details?id=com.pas.webcam
         
Step 2: Connect your phone and raspberry pi  in same network and start server in the app you will be displayed the ip address.

Step 3 : copy paste that ip address in chrome and select Javascript,"BOOM" you are connect now right click on the video frame and select copy image address that is your url which you have to change in code "Gesture.py"

