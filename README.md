Blood Vessel Detection in Retinal Fundus Images

Project Overview

This project focuses on the detection of blood vessels in retinal fundus images to aid in the diagnosis of critical ocular diseases such as diabetic retinopathy and glaucoma. The implementation is done in Python using libraries like OpenCV, NumPy, and Matplotlib for image processing.

Methodology
 - The green channel of the image is used for processing due to its higher sensitivity in detecting blood vessels.
 - Image preprocessing includes Contrast Limited Adaptive Histogram Equalization (CLAHE) and Gaussian filtering to enhance vessel visibility.
 - Morphological operations such as erosion and dilation are applied to improve segmentation quality.
 - The final output provides a clear and high-contrast segmentation of the blood vessels.

Input & Output
Input: A color retinal fundus image.
Output: A binary map highlighting the detected blood vessels.

Technologies Used: 
- Python
- OpenCV
- NumPy
- Matplotlib

Keywords:
blood vessel detection, retinal fundus images, image processing, diabetic retinopathy, glaucoma
