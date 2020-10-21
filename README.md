# esp32-cam-photo
Example inspired on https://devopstar.com/2020/05/16/aws-iot-esp32-cam-setup to send a photo when a message is published in an AWS IoT Core topic. 
Please go to https://devopstar.com/2020/05/16/aws-iot-esp32-cam-setup for a step by step guide to send a photo to AWS IoT Core. 
I've modified the code to only send a photo when a message is published into the topic "users/sos/image". That's why the device is subscribed 
to the topic in the setup function. Other than that, the code is the same as in the before cited blog.
