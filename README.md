# Mask_detection
This project sheds light on object detection and instance segmentation using the YOLO (you only live once) family of models, focusing primarily on fine-tuning a custom dataset for mask detection. My main goal is to turn mask-wearing statuses into three types: masks, no masks, and incomplete masks (masks that are being worn in the wrong manner). I trained custom YOLOv5 and YOLOv8 models with a custom dataset to see the pros and cons of each model in real-world scenarios. 

# Training Configurations: 
The experiments involved four different training sessions with different configurations.

Training with yolov5n.pt: YOLOv5 pretrained Detect model which Trained with COCO dataset. First training completed with this model with detection and classification capabilities without segmentation.

Training with yolov5n-seg.pt: YOLOv5 pretrained Segment models which Trained with COCO dataset. Not only detect object but also mark full object each and every pixel.

Training with yolov8n.pt: YOLOv8, which is the one of the latest version of YOLO, pretrained Detect model which Trained with COCO dataset. 

Training with yolov8n-seg.pt: YOLOv8 pretrained Segment models which Trained with COCO dataset. Not only detect object but also mark full object each and every pixel.
