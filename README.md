# Object-Recognition-Algorithms

Object reconition is a computer vision method of identifying the different classes or types of objects in an image and locating them using bounding boxes. This Repository contains programs of four Object Recognition Algorithms - RCNN (Region based Convolutional Neural Network), YOLO (You Only Look Once) - V3, V5 and V7 to run on COCO datasets.  

Explanation of the algorithms and comparative analysis is given in the paper: [Comparative Evaluation of Different Object Recognition Algorithms](https://drive.google.com/file/d/1OFUoL51_X4K_tcIJEsGSwNCqGvGfJasF/view?usp=share_link)

When you are training the model on custom dataset, you also need to upload dataset images and annotations file to colab storage. For YOLO v3, yolov3.cfg file needs to be updated according to the customization needed. In YOLO v5 and v7, .yaml files need to be updated, which contains names of the classes along with class ids and path to the train, test and validation datasets.   

To run the algorithms, copy the code on google colab notebook. Add the input image in the colab file and you are ready to detect the objects present in the input image. Do not forget to change the image name in the code according to the input image. 
