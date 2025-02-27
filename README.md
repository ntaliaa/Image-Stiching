Image Stitching using SIFT and RANSAC
Project Overview
This project implements an image stitching algorithm to create a panoramic image from N overlapping images. The process involves detecting keypoints, computing transformations, and blending the images into a seamless panorama.

Methodology
The image stitching pipeline consists of the following steps:

Feature Detection & Matching

Detect keypoints and descriptors using SIFT (Scale-Invariant Feature Transform).
Match features between overlapping images.
Homography Estimation

Use the RANSAC (Random Sample Consensus) algorithm to estimate the homography matrix.
Filter out outliers to improve alignment accuracy.
Image Warping & Stitching

Apply perspective transformations to align images.
Warp images into a common reference frame.
Blending Techniques

Experiment with different blending methods (e.g., linear blending, multi-band blending) to achieve smooth transitions.
Features
Automatic feature detection and matching.
Robust outlier removal with RANSAC.
Perspective transformation for precise alignment.
Multiple blending techniques for seamless stitching.
