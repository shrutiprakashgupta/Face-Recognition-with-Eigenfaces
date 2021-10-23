# Face-Recognition-with-Eigenfaces
Python Implementation of Viola Jones Algorithm for Face Recognition

## Training and Testing Data 
The following algorithm takes people's images with different emotions, and then uses the concept of Eigneface to find out similarity among them and further identify them. The image dataset is provided in the repo, which is taken from [Yale Face Dataset](https://www.face-rec.org/databases/). A training and (exclusive) test set is generated randomly out of the dataset for testing the performance of the algorithm.

## Implementation
The algorithm uses a [Haar-Cascade Filter](https://www.pyimagesearch.com/2021/04/12/opencv-haar-cascades/) in the beginning to crop out the face from images. Then it finds the similarities between images using the concept of [Eigenfaces](https://sites.cs.ucsb.edu/~mturk/Papers/mturk-CVPR91.pdf) and [Viola-Jones](https://ieeexplore.ieee.org/document/990517) Algorithm, and attempts to identify the person. The performance is calculated as the percentage accuracy of the algorithm in detecting the faces. 
