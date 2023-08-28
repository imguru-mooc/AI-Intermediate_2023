
Aerial Solar Panels - v13 2023-02-23 2:33pm
==============================

This dataset was exported via roboflow.com on March 9, 2023 at 1:24 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand and search unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

For state of the art Computer Vision training notebooks you can use with this dataset,
visit https://github.com/roboflow/notebooks

To find over 100k other datasets and pre-trained models, visit https://universe.roboflow.com

The dataset includes 179 images.
Solar-panels are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:

The following augmentation was applied to create 4 versions of each source image:
* Randomly crop between 0 and 42 percent of the image
* Random brigthness adjustment of between -50 and +50 percent

The following transformations were applied to the bounding boxes of each image:
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -45 and +45 degrees


