# Biometrics

This repository hosts two projects that dive into the realm of biometric identification using signature and fingerprint analysis. By leveraging image processing techniques and pattern recognition, these projects aim to establish secure and accurate identification systems.

## Projects Overview

### Reseach Work (Accepted) in Open Set Masked Face Identification System

<p align='center'>
<img width="837" alt="image" src="https://mobidev.biz/wp-content/uploads/2023/03/how-masked-face-recognition-works.png">
</p>

This was a project to create a system to identify individuals who are genuine vs imposters, while wearing face masks. This project was inspired by the COVID 19 pandemic, which was a serious health risk that prompted people to start wearing masks. Our contribution was the new dataset that we created as well as the results, which classified imposters accurately.

The contributors to this project were:
1. Aryan Bhapkar
2. Manasi Pawaskar
3. Dev Chandan


## Dataset
We created our dataset by combining two Datasets which were publically available.
CASIA Web Face and CASIA Web Masked Face
Here is the link to our Dataset: 
https://drive.google.com/file/d/1yMgSIg9bnUwzot8ZFcxXcjmXl_OSWiyT/view?usp=share_link

## Presentations
[1st Presentation](https://www.canva.com/design/DAFfSnIccLQ/MmD0DOumTdVn39tNuE9t1Q/edit?utm_content=DAFfSnIccLQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

[Research Paper Presentation (with references)](https://docs.google.com/presentation/d/1nxSF2kWtjcuxbOpirdclmEtanVKwD6VsE2dbr2NGD-o/edit?usp=sharing)

[Research Paper Pdf](https://drive.google.com/file/d/1DS-qcZlO-CYybxoWVvXHTjpTXjc6JJh1/view?usp=sharing)


### Signature Forge Detection

This project is designed to detect signature forgeries using structural similarity indexes and image processing methods. It demonstrates the ability to differentiate between genuine and forged signatures effectively.

<img width="837" alt="image" src="https://github.com/dev02chandan/Biometrics/assets/73015720/3175e034-905f-49ce-8318-917c51c2b7ee">

#### Steps Involved:

1. Import Dataset
2. Perform Canny Edge Detection
3. Apply Morphological Operations for image enhancement
4. Compute Structural Similarity Index of genuine and Forged Signatures

### Fingerprint Identification System

The goal of this notebook is to develop a fingerprint identification system. The system processes the fingerprint images, enhancing and extracting unique features such as minutiae to match fingerprints with high precision.

![Image of Fingerprint Biometrics](https://media.istockphoto.com/id/1299730469/photo/fingerprint-biometric-authentication-button-digital-security-concept.jpg?s=612x612&w=0&k=20&c=5N69O1YqbcAw2ZHV1oVeItoagXth9YNxF_Dnfn_pwUI=)

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

