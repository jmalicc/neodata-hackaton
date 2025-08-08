Hackaton which was organized as a part of Neodata workshop at Faculty of Electrical Engineering and Computing in Zagreb in december 2024.
All non-code files are in Croatian
I cant put the pictures used for training or the final model on the github because files are too large

WINNING STRATEGY:
The starting image set contained 50 images and their respective binary counterparts, which is too small of a dataset to teach any model. 
The question was how do we use the 50 images we have to as efficiently teach the model to recognize the specific parts on the image using binary classification.
Using basic image transformations, such as 90, 180 and 270 degree rotations, mirroring on both sides, and image skewering, we turned the original 50 image dataset into 1600 images paired with their respective binary versions.
From there, it was a simple train the model and modify the parameters to get the best possible results under 24h.
