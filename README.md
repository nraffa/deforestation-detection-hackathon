# Grocery Object Detection Model

Objective: train a simple object detection model to identify instances of products in a given image. This notebook will attempt to locate and classify occurrences of different products in supermarket shelves using a subset of the Grozi-3.2K dataset

## Reproducibility

- Special care for the directory where the repository of the algorithm used is cloned

>dir_to_project >> parameter to complete with the directory of the project

>dir_to_repo >> parameter to complete with the directory of the repo cloned

```
project -- grozi_coco -- images -- train
        |       |            |----- validation
        |       |
        |       |-------- labels -- train
        |                    |----- validation    	
       yolov5
```
## Notebook
Notebook created in Google Colab which can be here: 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Aa-CJCNzP3gkYoIvphH_BJhTHC2PMboy?usp=sharing)

## Sources 

- Maindola, G., 2022. Introduction to YOLOv5 Object Detection with Tutorial - MLK - Machine Learning Knowledge. [online] Machinelearningknowledge.ai. Available at: <https://machinelearningknowledge.ai/introduction-to-yolov5-object-detection-with-tutorial/> [Accessed 24 March 2022].

- Gandhi, R., 2018. R-CNN, Fast R-CNN, Faster R-CNN, YOLO — Object Detection Algorithms. [online] Medium. Available at: <https://towardsdatascience.com/r-cnn-fast-r-cnn-faster-r-cnn-yolo-object-detection-algorithms-36d53571365e> [Accessed 24 March 2022].

- Gur Arie, L., 2022. The practical guide for Object Detection with YOLOv5 algorithm. [online] Medium. Available at: <https://towardsdatascience.com/the-practical-guide-for-object-detection-with-yolov5-algorithm-74c04aac4843> [Accessed 24 March 2022].

- Cochard, D., 2021. YOLOv5 : The Latest Model for Object Detection. [online] Medium. Available at: <https://medium.com/axinc-ai/yolov5-the-latest-model-for-object-detection-b13320ec516b> [Accessed 29 March 2021].

- Yohanandan, S., 2020. mAP (mean Average Precision) might confuse you!. [online] Medium. Available at: <https://towardsdatascience.com/map-mean-average-precision-might-confuse-you-5956f1bfa9e2> [Accessed 24 March 2022].

- GitHub. 2021. GitHub - ultralytics/yolov5: YOLOv5 🚀 in PyTorch > ONNX > CoreML > TFLite. [online] Available at: <https://github.com/ultralytics/yolov5> [Accessed 30 March 2022].