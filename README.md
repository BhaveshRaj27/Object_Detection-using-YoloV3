# Object_Detection-using-YoloV3
Here Transfer Learning is used to create the object detection using YOLOV3. The code is well described. The two code are provide one for real time detection and other is for detection on image. I can create the code from scratch but training it required high machine power which I don't have i can provide the code from scratch if somebody interested.

# Step to follow
1. Download YoloV3 weights, configration and names of classes. For classes download from coco.names and For configration download yolov3.cfg. Download weights from https://pjreddie.com/darknet/yolo/. Download yolov3-416 which I have used.
2. Use the code in repository. Follow it line by line. Explaination is provided in the code.
3. Result
    ![](https://github.com/BhaveshRaj27/Object_Detection-using-YoloV3/blob/main/Image/result.jpg)
 
 Note: 1. Remember to convert predction value(shown as confidences in code ) into float else get system error.
       2. Convert output of non_maximal_suppression into numpy array otherwise error occur when use flatten if no object will be found in image.
   
