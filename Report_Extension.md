# Summary of Reports

## R-CNNs

Region-based Convolutional Neural Networks (R-CNN) are widely used in video detection and image segmentation.

- **R-CNN**: Create regions of interest by region proposal method. Can be slow when there are many proposals.
- **Fast R-CNN**: Achieve near real-time rates. Cheaper and quicker than RCNN. Not flexible and may still be slow.
- **Faster R-CNN**: Make use of Region Proposal Networks.
- **Mask R-CNN**: Add a predicting branch to existing recognition branches. Flexible and fast. May fail in dense and similar scenes.
- **Rotated Mask R-CNN**: A good bounding box contains just one object in that class.

## YOLO

You Only Look Once (YOLO). A relatively fast and accurate real-time objects detection approach. Can simply resize the model to get higher speed or accuracy.

## A Deep Unsupervised Learning Algorithm Based on Cloud Computing

It can increase the efficiency of NN learning, especially can shorten the running time. It still needs further improvement on accuracy enhancement and has some points to be optimized.

## Some Advanced K-Means Algorithms

### K-Means++

Assuming that there are n+1 center points to pick. 
Choose first n centers, then get the n+1 as far as possible away from the n points. 

Compared to K-Means: K-Means picks all n+1 points randomly.

### Kernel K-Means

Get all data in another space then work on it.

### ......
