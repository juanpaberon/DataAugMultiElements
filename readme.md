<h1>Data Augmentation by Cropping Images</h1>

The objective of this repository is to set up a method to increase the number images for training a computer vision model. The computer vision model has to identify the location and the type of certain objects in an image. The images can have more than one object of interest and more than one class. The idea is to create new images from old ones by cropping them, but the cropping has to be done according to the content of the image.

The strategy is to implement a clustering method such as DBSCAN to group the objects of interest and crop the image to separate each group. Other options could be set up such as having more than one group in the cropped image, etc. The first step is to define the distance to be used.