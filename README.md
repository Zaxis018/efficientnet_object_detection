Efficient_net was initially trained for image classification. Then it was compressed by 14x with channel pruning.<br>
The compressed model is used for object detection by the sliding window approach. different sized windows are slided in the target image and classification is done each time.
Only highly confident,non-overlapping bounding boxes are kept for each class
