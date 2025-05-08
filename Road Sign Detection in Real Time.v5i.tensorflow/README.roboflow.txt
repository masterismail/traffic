
Road Sign Detection in Real Time - v5 2024-11-05 5:12am
==============================

This dataset was exported via roboflow.com on March 16, 2025 at 2:42 AM GMT

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

The dataset includes 7980 images.
Traffic-Road-Signs are annotated in Tensorflow Object Detection format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)
* Grayscale (CRT phosphor)
* Auto-contrast via contrast stretching

The following augmentation was applied to create 3 versions of each source image:
* Random Gaussian blur of between 0 and 1.8 pixels
* Salt and pepper noise was applied to 1.93 percent of pixels


