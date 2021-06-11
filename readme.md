<h1>Data Augmentation by Cropping Images</h1>

The objective of this repository is to set up a method to increase the number images for training a computer vision model. The computer vision model has to identify the location and the type of certain objects in an image. The images can have more than one object of interest and more than one class. The idea is to create new images from old ones by cropping them, but the cropping has to be done according to the content of the image.

The strategy is to find groups of objects and crop the image so the new image contains the whole group. DBSCAN was chosen as the clustering method and its implementation is located in the folder clustering. A distance was designed for this clustering and its definition can be found in the folder distance