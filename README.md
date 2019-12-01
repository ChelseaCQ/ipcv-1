#  Detecting Dart Boards
- The programs were created using C++ and OpenCV2.
#  Setup
- Detect faces: select frontalface.xml as cascadeeClassifier and compile task1.cpp. 
- Find ground truth:  use findgroundtruth.cpp to get positions of red boxes. 
- Detect dart boards:  select cascade_500.xml as cascadeeClassifier and compile task2.cpp. 
- Hough transform:  use hough_detect.cpp to get results after hough transform
## compile and run
#### g++ face.cpp /usr/lib64/libopencv_core.so.2.4 /usr/lib64/libopencv_highgui.so.2.4 /usr/lib64/libopencv_imgproc.so.2.4 /usr/lib64/libopencv_objdetect.so.2.4 
#### ./a.out dart1.jpg
