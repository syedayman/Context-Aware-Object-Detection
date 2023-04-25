# Context-Aware-Object-Detection
The presence of an object in real life is rarely in solitude, they co-vary with other objects and its surroundings creating an abundant source of contextual information, such as associations and correlations. Humans build scene representations over time using information gained through contextual inference and analysis to identify regions of interest in visual media. Attempts to reproduce this process using Artificial Intelligence is the inspiration behind the state-of-the-art 
Object Detection algorithms of today. Context plays a major role in the way humans perceive the world; hence it is rational to assume that the provision of contextual information in the object detection algorithm can only enhance its performance.

In this project, the training algorithm of an object detection model is enhanced by integrating contextual information in the form of ‘scene labels’, through various methods to identify the most optimal approach. A total of four deep learning models are implemented and from among the two contextually aware object detection models, the best performing model produced a classification accuracy of 75.14% and a mean bounding box IoU of 0.69 on the constructed dataset. This was achieved by virtue of an auxiliary scene classification model used to make image scene predictions in the training phase.


## Repository structure

**Project Report:** dissertation.pdf

**Scene Classification Dataset:** IC (image classification)

**Object Detection Dataset:** OD (object detection)

**Deep Learning Models:**
- Scene Classification Model
- Object Detection Model
- Context-Aware Model 1
- Context-Aware Model 2
