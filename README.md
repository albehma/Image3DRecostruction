# Image3DRecostruction
SfM: implementation of a SURF features extractors for test images (fountain and tiso) saved in a .txt file suitable for colmap, and features matching saved in a .txt file suitable for colmap.

As in the description, the purpose of this piece of code is to extract SURF features in order to pass it to an autoencoder previously generated using Neural Network.
The resulting keypoints are given to Colmap to get a 3D reconstruction of the image.
