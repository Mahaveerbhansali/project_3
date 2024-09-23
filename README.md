Image Segmentation Using Region Growing and Merging
This project uses the Region Growing and Region Merging algorithms to develop picture segmentation techniques. By beginning at a seed point (Region Growing) and combining neighboring areas that satisfy a similarity threshold (Region combining), these techniques enable the identification of regions in an image based on similarity.

Features
Region Growing: Based on pixel similarity, the region is grown by segmenting the image from a seed point.
Region merging is the process of combining neighboring areas from a first threshold-based segmentation.
Interactive Input: To view the real-time outcomes of region expanding and merging, users can upload photos and apply thresholds and random seed points.
Image processing: This technique turns photos into grayscale and effectively uses algorithms to show segmentation.

Dependencies
Python 3.x
OpenCV
Numpy
Matplotlib
Skimage (for region merging)
Google Colab (for file uploads if using Colab)
