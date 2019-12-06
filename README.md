#  Horizontal Scaling for an Embarrassingly Parallel Task:Blockchain Proof-of-Work in the Cloud
- created using C++ and OpenCV2.
- See the included report for a full writeup
#  Setup
- Find ground truth:  Use findgroundtruth.cpp to get positions of red boxes.
- Detect faces: Select frontalface.xml as cascadeeClassifier and compile task1.cpp. Input an image as argv
- Detect dart boards:  Select cascade_500.xml as cascadeeClassifier and compile task2.cpp. Input an image as argv
- Detect dart boards (improved in task3):  Select cascade_500.xml as cascadeeClassifier and compile task3.cpp. 
- Detect dart boards (improved in task4):  Select cascade_500.xml as cascadeeClassifier and compile task4.cpp. 
- Hough transform:  Use hough_detect.cpp to get results after hough transform.
## compile and run
#### g++ task2.cpp /usr/lib64/libopencv_core.so.2.4 /usr/lib64/libopencv_highgui.so.2.4 /usr/lib64/libopencv_imgproc.so.2.4 /usr/lib64/libopencv_objdetect.so.2.4 
#### ./a.out dart1.jpg
