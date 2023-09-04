# Apple-Detection-in-MinneApple-Dataset-with-YOLOv8

## Introduction
In modern agricultural practices, advanced machine learning techniques play a pivotal role in optimizing yields and management. A significant challenge in orchard management is detecting apples on trees, essential for effective harvest planning and yield estimation. The YOLO series, especially the YOLOv8 model, stands out as a state-of-the-art solution for object detection, but its potential in orchards remains untapped. Addressing this, our study evaluates YOLOv8's capability in orchard apple detection, aiming to set a benchmark. By employing image augmentation techniques like exposure, rotation, mosaic, and cutout, we lifted the model's performance to a state-of-the-art level. We further integrated multi-task learning, enhancing tree apple detection by also identifying apples on the ground. This approach resulted in a model with robust accuracy across evaluation metrics. Our results underscore that the YOLOv8 model achieves a leading standard in orchard apple detection. When trained for both tree and fallen apple detection, it outperformed the one when trained exclusively for the former. Recognizing fallen apples not only reduces waste but could also indicate pest activity, influencing strategic orchard decisions and potentially boosting economic returns. Merging cutting-edge tech with agricultural needs, our research showcases the promise of multi-task learning in fruit detection with deep learning.

## Files Structure
- Code
	- MinneApple\_Original.ipynb: train and evaluate YOLOv8 model
	- MinneApple\_Small.ipynb: train and evaluate STL model
	- MinneApple\_Ground.ipynb: train and evaluate MTL model
	- Results.ipynb: evaluate final best models
- Model
	- On the original dataset:
		- Original\_original\_best.pt
		- Original\_augmented\_best.pt
	- On randomly selected subset:
		- Small\_original\_best.pt
		- Small\_augmented\_best.pt
	- On fallen apple labelled subset:
		- Ground\_original\_best.pt
		- Ground\_augmented\_best.pt

## Results
![Apple-Detection-in-MinneApple-Dataset-with-YOLOv8/img/results.png](Apple-Detection-in-MinneApple-Dataset-with-YOLOv8/img/results.png)

