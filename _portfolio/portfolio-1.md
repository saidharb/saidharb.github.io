---
title: " Improving Object Detection Performance on Hard to Detect Instances in DOTA"
excerpt: "This project improved mean Average Precision (mAP) for hard-to-detect instances in the DOTA dataset. I implemented dataset augmentation (oversampling, copy-pasting hard-to-detect objects and their bounding boxes within images), preprocessing pipelines, training routines, object detection evaluation metrics, and post-processing in PyTorch to train a YOLOv5 model for object detection. The approach increased mAP for hard-to-detect instances significantly in comparison to the baseline. ([Paper](http://saidharb.github.io/files/improving_htd_DOTA.pdf), [Code](https://github.com/saidharb/DOTA-Improve_hard_to_detect_instances_performance/tree/master))<br/><img src='/images/OD_HTD_2.png'>"
collection: portfolio
---

This work was done for the Deep Learning course taught by Dr. Pedro Diaz and Dr. Mehdi Maboudi at TU Braunschweig during the summer semester of 2024. You can find the link to the paper [here](http://saidharb.github.io/files/improving_htd_DOTA.pdf) and the code in this [GitHub repository](https://github.com/saidharb/DOTA-Improve_hard_to_detect_instances_performance/tree/master).
