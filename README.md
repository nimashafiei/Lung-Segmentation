

# Lung Segmentation in CT Scans using Python

This repository contains Python code for segmenting lung CT scans. The code uses the pydicom library to read in DICOM images, and then applies various image processing techniques such as normalization, K-means clustering, erosion, dilation, and label extraction to isolate the lungs from the rest of the image. The resulting binary mask is then applied to the original image to highlight the lungs.
This repository contains Python code for segmenting lung CT scans.

Requirements
- Python 3.6 or higher
- Pydicom
- Matplotlib
- Numpy
- Scikit-image
- Scikit-learn
- OpenCV
- Usage

To use this code, clone the repository and install the required libraries using pip.
