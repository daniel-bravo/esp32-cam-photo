# esp32-cam-photo
Example inspired on https://devopstar.com/2020/05/16/aws-iot-esp32-cam-setup to send a photo when a message is received in an IoT topic
Plese go to https://devopstar.com/2020/05/16/aws-iot-esp32-cam-setup for a step by step guide to know how to send a photo to IoT core. 
I modified the code to only send a photo when a message is published into the topic users/sos/image. That's why the device is subscribed 
to the topic in the setup function. Other than that, the code is the same as in the before cited blog.
