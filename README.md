# People-Counter
It does what the name says it does, man. It counts people.

# Methode
By using YOLOv4, which is a real-time object detection model published in April 2020 that achieved state-of-the-art performance on the COCO dataset. It breaks the object detection task into two pieces: regression to identify object positioning via bounding boxes and classification to determine the object's class. This implementation of YoloV4 uses the Darknet framework.

By using YOLOv4, we are implementing many of the past research contributions in the YOLO family along with a series of new contributions unique to YOLOv4, including new features: WRC, CSP, CmBN, SAT, Mish activation, Mosaic data augmentation, CmBN, DropBlock regularization, and CIoU loss. In short, with YOLOv4, you use a better object detection network architecture and new data augmentation techniques.

# The Why

My sister went to work at a Fortune 500 company that specializes. Security and she talked about security cameras that could watch people and monitor their behavior to detect whether they were a threat. This peaked my interest so I created a simplified version that would be able to count the amount of people going in and out of an area.


# Library Used
The used library is https://github.com/bytedeco/javacv
