# Mask_detection
This project sheds light on object detection and instance segmentation using the YOLO (you only live once) family of models, focusing primarily on fine-tuning a custom dataset for mask detection. My main goal is to turn mask-wearing statuses into three types: masks, no masks, and incomplete masks (masks that are being worn in the wrong manner). I trained custom YOLOv5 and YOLOv8 models with a custom dataset to see the pros and cons of each model in real-world scenarios. 

# Training Configurations: 
The experiments involved four different training sessions with different configurations.

Training with yolov5n.pt: YOLOv5 pretrained Detect model which Trained with COCO dataset. First training completed with this model with detection and classification capabilities without segmentation.

Training with yolov5n-seg.pt: YOLOv5 pretrained Segment models which Trained with COCO dataset. Not only detect object but also mark full object each and every pixel.

Training with yolov8n.pt: YOLOv8, which is the one of the latest version of YOLO, pretrained Detect model which Trained with COCO dataset. 

Training with yolov8n-seg.pt: YOLOv8 pretrained Segment models which Trained with COCO dataset. Not only detect object but also mark full object each and every pixel.

# summery
This project applied YOLO models (YOLOv5 and YOLOv8) for mask detection with success. It used instance segmentation to boost classification accuracy. YOLOv8n models, mainly in object detection, which model has issue that out of all object that were present in photos cannot detect correctly but it overcome by fine tuning that make best model for object detection, showed great promise. As same YOLOv5n-seg is best for instant segmentation, as this model also have issue of all object that were present in photos cannot detect correctly but it also solved as same as YOLOv8n. They classified mask-wearing states with high accuracy, making them fit for real-world use.

The results reveal the triumph of fine-tuning pre-trained YOLO models on custom datasets. They highlight how segmentation boosts model performance. This study advances mask detection systems. It sheds light on what modern object detection models can do.


# conclusion

I have successfully accomplished the project goal and obtained a good mask detection system by using YOLO models. specifically YOLOv5 and YOLOv8. From the brief particularly in outline requiring detailed object classification, it is shown that the consolidation of an instance segmentation is better. YOLOv5n-seg outperformed all of the other given models in the segmentation YOLOv5n-seg provided the highest accuracy and given its highest accuracy, it can be applied in real-time with the aim of healthcare monitoring. However, YOLOv8n is also showed best performance among other all model that I trained. The outcome of this work shows the benefits of using top deep learning models for object detection and instance segmentation. By adjusting these models to a special set of data, I could use their pre-trained knowledge and adapt it to the specific task.
