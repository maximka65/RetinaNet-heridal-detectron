# RetinaNet Object Detection on Heridal Dataset

## Overview

This project focuses on training a RetinaNet model using the Heridal dataset and the detectron framework. The goal is to achieve accurate object detection on the Heridal dataset and evaluate the model's performance using various metrics.

## Dataset

The Heridal dataset is a curated collection of images and corresponding bounding box annotations for object detection tasks. It covers a wide range of objects across different categories, providing diverse and representative samples for training and evaluation.

## Metrics

Based on the evaluation of the RetinaNet model on the Heridal dataset, the following metrics were achieved:

    Precision at IoU=0.5: 0.2165
    Recall at IoU=0.5: 0.167
    Mean Average Precision (mAP): 0.049
    Mean Average Precision at IoU=0.5 (mAP50): 0.069
    Mean Average Precision at IoU=0.75 (mAP75): 0.019
    Frames per Second (FPS): 10.29

These metrics provide insights into the model's precision, recall, average precision, and frame rate. The results demonstrate the effectiveness of the RetinaNet model in accurately detecting objects in the Heridal dataset.

## Acknowledgements

We would like to acknowledge the detectron framework and the Heridal dataset for their contribution to this project. Their resources and tools have been instrumental in achieving the desired results.