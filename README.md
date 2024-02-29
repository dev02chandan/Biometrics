# Biometrics Repository

This repository hosts two advanced projects that dive into the realm of biometric identification using signature and fingerprint analysis. By leveraging image processing techniques and pattern recognition, these projects aim to establish secure and accurate identification systems.

## Projects Overview

### Signature Forge Detection

This project is designed to detect signature forgeries using structural similarity indexes and image processing methods. It demonstrates the ability to differentiate between genuine and forged signatures effectively.

#### Steps Involved:

1. Import Dataset
2. Perform Canny Edge Detection
3. Apply Morphological Operations for image enhancement
4. Compute Structural Similarity Index of genuine and Forged Signatures

### Fingerprint Identification System

The goal of this notebook is to develop a fingerprint identification system. The system processes the fingerprint images, enhancing and extracting unique features such as minutiae to match fingerprints with high precision.

#### Steps Involved:

1. Fingerprint segmentation
2. Estimation of local ridge orientation
3. Estimation of local ridge frequency
4. Fingerprint enhancement
5. Detection of minutiae positions
6. Estimation of minutiae directions
7. Creation of local structures
8. Fingerprint comparison
9. Apply the entire process on a new dataset
10. Create a pipeline

## Getting Started

To utilize these notebooks:

1. Clone the repository.
2. Install any required dependencies listed in the notebooks.
3. Run the Jupyter Notebooks in an environment that supports Python and necessary libraries like OpenCV, NumPy, and SciPy.

## Prerequisites

- Familiarity with Python and Jupyter Notebooks
- Understanding of image processing and machine learning basics


## Contributing

We welcome contributions and suggestions. Feel free to fork the repository, make changes, and submit a pull request.

