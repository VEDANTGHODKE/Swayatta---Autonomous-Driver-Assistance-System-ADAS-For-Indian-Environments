### Dataset description

### Author - Vedant Ghodke


In comparison to the semantic segmentation that links each pixel of the image to a class label, we segment the image into a coarse grid of SxS cells. Each cell linked with a class label. In our work, we have chosen S=10 and only two classes. The first class represents a drivable surface while the second class is everything else. 

To create a labeled dataset, we used semantic segmented images (an image that has each pixel of the image linked to a class label). Then, we calculate the number of pixels in a cell that belong to the class representing the drivable surface. If the percentage of these pixels is higher than P percentage of all the pixels in the cell, we assign the cell said label. In our work, we have chosen P=50%. Since we have only two classes we can represent each cell label as binary 1 or 0
