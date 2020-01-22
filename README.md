# Segmentation of Lesions in 3D Brain Imaging Data with U-Net

Three-dimensional imaging approaches such as X-ray Computed Topography (CT) are widely used in both medical and research settings, and can generate vast quantities of high-resolution volumetric data. Manual annotation of 3-D volumes is extremely laborious and time-intensive, and therefore automated methods for segmenting volumetric imaging data are an important but challenging problem for machine learning.

As my final project in Harvard's [Advanced Machine Learning, Data Mining, and Artificial Intelligence (CSCI E-82)](https://canvas.harvard.edu/courses/52820/assignments/syllabus) course in Fall 2018, I developed a method to analyze X-ray computed topography (CT) images of rodent brains for the purpose of neuroscience research. Using Keras, I implemented a both a 2-D and 3-D U-Net (Ronneberger et al 2015, Çiçek et al 2016) and evaluated the performance of each algorithm on my rat brain dataset.

### Prerequisites

This code uses the following packages:

```
pip install keras pandas numpy skimage scipy
```

## Acknowledgments

This work lends code and/or inspiration from multiple sources:

2D U-Net
* Original paper: [Ronneberger et al 2015](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28)
* https://www.kaggle.com/keegil/keras-u-net-starter-lb-0-277
* https://github.com/jocicmarko/ultrasound-nerve-segmentation

3D U-Net
* Original paper: [Çiçek et al 2016](https://link.springer.com/chapter/10.1007/978-3-319-46723-8_49)
* https://github.com/ellisdg/3DUnetCNN
* 3D data augmentation https://stanford.edu/~shervine/blog/keras-how-to-generate-data-on-the-fly
