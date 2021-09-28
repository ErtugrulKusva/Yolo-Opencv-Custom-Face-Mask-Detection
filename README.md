# ErtugrulKusva/Yolo-Opencv--Custom-Face-Mask-Detection
 
![5fps_800cozunurluk](https://user-images.githubusercontent.com/60093326/135085613-a8260343-1bd4-4cd4-8eab-5ea71fde1510.gif)

In the project I created a dataset of 1000 photos. I have labeled this dataset in yolo format. I did a model tutorial using Yolov3 darknet tiny weight files. The weight file formed as a result of the model training was shared within the project.

The hardware used in model training and detection is as follows:

Graphics card: GTX 1650 Nvidia
Processor: AMD RYZEN 5 1600
Ram: 16GB
Operating system: WIN10 64 bit


About opencv:
*You must install the Opencv-Python library (If you want to use it with the GPU, you must also install the CUDA plugin. If you do not install it, it will work with the CPU.)

Performance:

Yolo-tiny(33 Mb) 608x608 resolution weight file = 55-60 FPS
Yolo-main(330 Mb) 416x 416 resolution weight file = 15-20 FPS

I am sharing the detection code, the weight file resulting from the training and the project outputs so that you can use the model which I created, in your own projects.


