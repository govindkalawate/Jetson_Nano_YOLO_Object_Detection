# Jetson_Nano_YOLO_Object_Detection

# NVIDIA Jetson Nano 

![image](https://user-images.githubusercontent.com/103236939/191592396-9962b527-aa4a-468c-8268-5a47074fa503.png)




The NVIDIA Jetson Nano Developer Kit is an AI computer for makers, learners, and developers that brings the power of modern artificial intelligence to a low-power, easy-to-use platform. Get started quickly with out-of-the-box support for many popular peripherals, add-ons, and ready-to-use projects.

We are grateful to NVIDIA and SRM Institute of Science and Technology for giving us the opportunity to work on this project.

# Setting up NVIDIA Jetson Nano 

![WhatsApp Image 2022-09-22 at 00 57 51](https://user-images.githubusercontent.com/103236939/191595021-465fa70c-fd5a-46da-9f7e-f784a5df2808.jpeg)


For setting up the kit for the first time we reffered to the tutorial made by the NVIDIA Developer - Video Link

Other than the kit we have connected some other required objects-

IMX-219-77 Camera Module Ethernet connection External Monitor/Display 32GB MicroSD Card HDMI Cable Power Adapter with Supply image Setting up YOLO-Object Detection We will be installing Darknet using the Jetson's terminal from AlexeyAB/darknet. git clone https://github.com/AlexeyAB/darknet.git cd darknet Enable GPU and OpenCV support by editing the Makefile and also compile the makefile- sudo nano Makefile Set the following values to enable GPU and OpenCV support-

GPU=1

CUDNN=1

OPENCV=1

make To run object detection with Darknet, we need a model config and model weights(in the cfg directory). wget https://pjreddie.com/media/files/yolov3.weights wget https://pjreddie.com/media/files/yolov3-tiny.weights We are done with installation part and we need to run the camera module to see the predictions in real time- detectnet-camera.py

# Results from our kit - 

https://user-images.githubusercontent.com/103236939/191591823-b9efcf22-0536-4c5e-8319-3456c71bcff6.mp4

# AUTHORS

# SAMUDRA BANERJEE

![WhatsApp Image 2022-09-13 at 17 25 05](https://user-images.githubusercontent.com/103236939/191592152-1fdbf37e-f717-4db6-b1c1-7b6af3ec436a.jpeg)


# GOVIND KALAWATE

![WhatsApp Image 2022-09-21 at 10 39 41](https://user-images.githubusercontent.com/103236939/191588461-e010b72c-aa35-4b5d-94ec-592846f45799.jpeg)


# OM WAGHMARE 

![image](https://user-images.githubusercontent.com/103236939/191588528-e351582e-4d88-47da-b907-12c1078249ca.png)


image
