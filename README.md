Welcome!
========

This repo describes how to access data for the paper "[Deep Neural Networks Rival the Representation of Primate IT Cortex for Core Visual Object Recognition](http://www.ploscompbiol.org/article/info:doi/10.1371/journal.pcbi.1003963)" by Charles F. Cadieu, Ha Hong, Daniel L.K. Yamins, Nicolas Pinto, Diego Ardila, Ethan A. Solomon, Najib J. Majaj, James J. DiCarlo and published in PLoS Computational Biology.

## Access to the data 
The following file contains the images and neural measurements used in the analysis.  Access can be found through this link:

[PLoSCB2014_data_20141216.zip](https://s3.amazonaws.com/cadieu-etal-ploscb2014/PLoSCB2014_data_20141216.zip)


There are currently 4 Matlab files each containing data for a different type of neural measurement: IT multi-units, IT single-units, V4 multi-units, and V4 single-units (we will release the DNN features soon).  Each Matlab file contains an array of neural responses (images x neural-unit) and a meta structure indicating the corresponding image id, the class the object in the image belongs to, and the train/test splits for that image.  The order of the records in meta corresponds to the order of the rows in the neural response matrix.  There are 10 train/test splits used in the experiments in the paper.  Therefore, each record in meta contains 10 numbers with a 1 indicating that the image is present in the training set and a 0 indicating it is present in the testing set for that split.  The images are PNGs under the /images subfolder in the archive file (.zip).

### Reference
```
Cadieu CF, Hong H, Yamins DLK, Pinto N, Ardila D, et al. (2014) Deep Neural Networks Rival the Representation of Primate IT Cortex for Core Visual Object Recognition. PLoS Comput Biol 10(12): e1003963. doi: 10.1371/journal.pcbi.1003963
```
The paper can be accessed [here](http://www.ploscompbiol.org/article/info:doi/10.1371/journal.pcbi.1003963).

### Contact
If you have any questions, concerns, comments, or suggestions for clarification, please contact the authors at cadieu at mit.edu and hahong at mit.edu.
