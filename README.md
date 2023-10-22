# People-Counter
It does what the name says it does, man. It counts people.

# Method
By using YOLOv4, which is a real-time object detection model published in April 2020 that achieved state-of-the-art performance on the COCO dataset. It breaks the object detection task into two pieces: regression to identify object positioning via bounding boxes and classification to determine the object's class. This implementation of YoloV4 uses the Darknet framework.

By using YOLOv4, we are implementing many of the past research contributions in the YOLO family along with a series of new contributions unique to YOLOv4, including new features: WRC, CSP, CmBN, SAT, Mish activation, Mosaic data augmentation, CmBN, DropBlock regularization, and CIoU loss. In short, with YOLOv4, you use a better object detection network architecture and new data augmentation techniques.

# The Why

My sister went to work at a Fortune 500 company that specializes. My sister talked about how security cameras could watch, count, and monitor people and their behavior to detect whether they were a threat. This piqued my interest, so I created a simplified version that could count the number of people going in and out of an area.

# Application
Using [this video](https://www.youtube.com/watch?v=gFRtAAmiFbE) and our algorithm we were able to roughly count how many people entered the area from 12:00 AM to 8:00 AM. 
![Amount of people over Time](https://github.com/OGPigeon/People-Counter/assets/53824654/f526d4ee-01f7-441f-b0c1-693126f191b1)

# Alogrith In Use
<img width="560" alt="2023-10-22_222903" src="https://github.com/OGPigeon/People-Counter/assets/53824654/386e9888-576b-4d6a-8d90-3a47f6d3333d">
<img width="577" alt="2023-10-22_222015" src="https://github.com/OGPigeon/People-Counter/assets/53824654/195f519c-9b15-4eb3-ad53-9a4a83690aa2">

# Library Used
The used library is https://github.com/bytedeco/javacv
