# Point-cloud-classification-with-PointNet

Classification, detection and segmentation of unordered 3D point sets i.e. point clouds.

Note: Open the notebook in colaboratory to see the trimesh output. Since Github is static HTML, it does not show the visualizations made using trimesh.

## Problem Context:

A point cloud is a set of data points in space. Point clouds are generally produced by 3D scanners, which measure many points on the external surfaces of objects around them. As the output of 3D scanning processes, point clouds are used for many purposes, including to create 3D CAD (Computer-aided design) models for manufactured parts, for metrology and quality inspection, and for a multitude of visualization, animation, rendering and mass customization applications.

Scene semantic segmentation, which refers to the problem of predicting pixel-wise label for input image. is the process of assigning a label to every pixel in the image. This is in stark contrast to classification, where a single label is assigned to the entire picture. Semantic segmentation treats multiple objects of the same class as a single entity.

Applying deep learning to point clouds for object classification and part/scene semantic segmentation.

## Dataset:

ModelNet10 model dataset, the smaller 10 class version of the ModelNet40 dataset is used.

"http://3dvision.princeton.edu/projects/2014/3DShapeNets/ModelNet10.zip"

## This notebook is an implementation of:

https://keras.io/examples/vision/pointnet/

## Project Overview:

1- Exploratory Data Analysis

2- Building the PointNet Model

3- Training the PointNet Model

4- Predictions
