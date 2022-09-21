# Jetson_Nano_YOLO_Object_Detection

# Object-Detection-in-Jetson-Nano NVIDIA Jetson Nano jetson



The NVIDIA Jetson Nano Developer Kit is an AI computer for makers, learners, and developers that brings the power of modern artificial intelligence to a low-power, easy-to-use platform. Get started quickly with out-of-the-box support for many popular peripherals, add-ons, and ready-to-use projects.

We are grateful to NVIDIA and SRM Institute of Science and Technology for giving us the opportunity to work on this project.

# Setting up NVIDIA Jetson Nano

For setting up the kit for the first time we reffered to the tutorial made by the NVIDIA Developer - Video Link

Other than the kit we have connected some other required objects-

IMX-219-77 Camera Module Ethernet connection External Monitor/Display 32GB MicroSD Card HDMI Cable Power Adapter with Supply image Setting up YOLO-Object Detection We will be installing Darknet using the Jetson's terminal from AlexeyAB/darknet. git clone https://github.com/AlexeyAB/darknet.git cd darknet Enable GPU and OpenCV support by editing the Makefile and also compile the makefile- sudo nano Makefile Set the following values to enable GPU and OpenCV support-

GPU=1

CUDNN=1

OPENCV=1

make To run object detection with Darknet, we need a model config and model weights(in the cfg directory). wget https://pjreddie.com/media/files/yolov3.weights wget https://pjreddie.com/media/files/yolov3-tiny.weights We are done with installation part and we need to run the camera module to see the predictions in real time- detectnet-camera.py

# Results from our kit -

 WhatsApp.Video.2022-09-19.at.19.46.41.1.mp4 
# AUTHORS

# SAMUDRA BANERJEE

![WhatsApp Image 2022-09-13 at 17 25 05](https://user-images.githubusercontent.com/103236939/191588253-28b00483-34be-4092-bf1d-e20ab90933a0.jpeg)


# GOVINDH KALAWATE

![WhatsApp Image 2022-09-21 at 10 39 41](https://user-images.githubusercontent.com/103236939/191588461-e010b72c-aa35-4b5d-94ec-592846f45799.jpeg)


# OM WAGHMARE 

![image](https://user-images.githubusercontent.com/103236939/191588528-e351582e-4d88-47da-b907-12c1078249ca.png)


image
