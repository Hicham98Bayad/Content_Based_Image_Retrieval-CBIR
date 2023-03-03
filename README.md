# Content_Based_Image_Retrieval-CBIR

A CBIR system is organized in two parts:<br>
1-Off-line phase often called indexing where for each image a descriptor vector will be extracted and
extracted and saved as an index database<br><br>
<b>2-Online phase:</b> this is the search for similar images for a query image.<br> The same type
descriptor will be extracted from the query image and compared with the index database.<br>
Two main steps are to be taken into consideration when developing a
CBIR system. The first is the nature of the descriptors (features) to be used to form the
base of indexes. And the second is the similarity measure to be used to search for the most similar images for a
similar to a query image.<br> Indeed the search is done by measuring the distance between
descriptors instead of images.<br>
The descriptors used to form the indexes base are low level descriptors, namely ;
shape, color and texture.<br> And the similarity measure used can be a simple Euclidean distance
Euclidean distance or a multidimensional projection. <br><br>
<b>2 Image database </b>
For this workshop we will use the COREL image database which contains 10800 images and which is
classified in 80 groups of images. This database is a perfect tool to understand the fundamentals of
CBIR.<br><br>
<b>3 Implementation</b><br>
In order to develop a CBIR system robust to the transformations that the images can undergo, we have opted for
images, we have chosen Matlab as working environment.<br>
The first step is the indexing and the first code to write is to loop over the images of the
database to extract from each one a suitable descriptor vector.<br>
My first advice is to copy the image database to the default Matlab folder to avoid access errors.<br>
to avoid access errors. My second advice is not to write the code directly on the
but rather to create a *.m file, modify it and execute it as we go along.<br>
progress of this workshop.
