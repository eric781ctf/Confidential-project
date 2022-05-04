# Confidential-project

In this project, we try to detect whether there is any residual chips on the chipboards by using image processing.
Due to confidential, we can't release the original photos online.

## Data augmentation
The original images data wasn't enough for testing the method we use or even Machine Learning.
Thus, we used morphological, subtraction, exposure, and the different temperature of photo to augmentation our data.

## Distance
After preprocess of photos, we calculate the SIFT between two chipboards, one of them are the clean one, to check if we can figure out the residual chips on it.
