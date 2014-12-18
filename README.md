Welcome!
========

This repo describes how to access data for the paper "Deep Neural Networks Rival the Representation of Primate IT Cortex for Core Visual Object Recognition" by Charles F. Cadieu, Ha Hong, Daniel L.K. Yamins, Nicolas Pinto, Diego Ardila, Ethan A. Solomon, Najib J. Majaj, James J. DiCarlo and published in PLoS Computational Biology.

## Access to the data 
The following file contains the images and neural measurements used in the analysis.  Access can be found through this link:

[temporarylink.zip](dicarlolab.mit.edu)


There are currently 4 Matlab files each containing data for a different type of neural measurement: IT multi-units, IT single-units, V4 multi-units, and V4 single-units.  Each Matlab file contains an array of neural responses (images x neural-unit) and a meta structure indicating the corresponding image id and the train/test splits for that image.  The order of the records in meta corresponds to the order of the rows in the neural response matrix.  There are 10 train/test splits used in the experiments in the paper.  Therefore, each record in meta contains 10 numbers with a 1 indicating that the image is present in the training set and a 0 indicating it is present in the testing set for that split.

### Reference
To be posted.

### Contact
If you have any questions, concerns, comments, or suggestions for clarification, please contact the authors at cadieu at mit.edu and hahong at mit.edu.
