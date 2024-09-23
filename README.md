RegionSeg: Image Segmentation with Region Growing and Merging

Image Segmentation Using Region Growing and Merging
This project uses the Region Growing and Region Merging algorithms to develop picture segmentation techniques. By beginning at a seed point (Region Growing) and combining neighboring areas that satisfy a similarity threshold (Region combining), these techniques enable the identification of regions in an image based on similarity.

Features
A seed-based method known as "region growing" enlarges areas by including nearby pixels that meet a certain threshold.
Region Merging: An approach that improves the segmentation outcomes by combining previously segmented regions according to pixel similarity,allowing for the segmentation of color and grayscale pictures.
Random seed generation and adjustable threshold allow for dynamic testing.
For picture pre-processing, interpolation methods such as ARBH and Laplacian as well as enhancement functions like contrast and brightness modification are utilized.
Image processing: This technique turns photos into grayscale and effectively uses algorithms to show segmentation.

Dependencies
Python 3.x
OpenCV
Numpy
Matplotlib
opencv-python
skimage
scipy
Skimage (for region merging)
Google Colab (for file uploads if using Colab)
