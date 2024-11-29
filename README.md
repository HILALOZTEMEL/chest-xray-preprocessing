# Chest Xray Preprocessing


# Overview

This project involves working with the ChestX-ray8 dataset, which includes chest X-ray images. The primary objective is to preprocess these images for further analysis, focusing on techniques such as resizing, normalization, and edge detection. This repository serves as the midterm submission for a course in digital image processing.

# Dataset

The dataset used in this project is the ChestX-ray8 dataset. Below is an example of a chest X-ray image:



This dataset is widely used for medical image analysis and includes metadata for associated conditions. For this midterm, we focus on preprocessing the images for potential diagnostic applications.

# Steps and Methods

**1. Data Loading**

    ![image](https://github.com/user-attachments/assets/d16fb731-72c4-4220-8aa9-fc14ed9e3fac)


The dataset is loaded using Python's data manipulation libraries. Key libraries used include:

Pandas: For handling tabular data.

OpenCV: For image processing operations.


**2. Image Preprocessing Techniques**

- **Statistical Analysis**: Randomly selected 9 images were analyzed to compute statistical properties such as maximum, minimum, mean, and standard deviation.

  ![image](https://github.com/user-attachments/assets/b3309f3d-7647-4db9-8c98-ee3c9ef06cba)


- **Histogram Visualization**: Histograms were plotted for 9 randomly selected images.

  ![image](https://github.com/user-attachments/assets/6c89a6ae-57eb-4a9a-baa2-6d8383160804)


- **Contrast Stretching**: Contrast stretching was applied to all images to enhance details.
  
- **Gamma Transformation**: Gamma transformation was applied to contrast-stretched images.

  ![image](https://github.com/user-attachments/assets/a8f65490-08be-4398-8046-be98d957d4e7)

  

- **Median and Gaussian Blur**: Median and Gaussian blur were applied to all images for noise reduction.

  ![image](https://github.com/user-attachments/assets/560ff19f-2178-40eb-86c1-35085ca1302a)


- **Rotation and Flipping**: Images were rotated randomly by degrees ranging from 0 to 10 and flipped horizontally or vertically.

  ![image](https://github.com/user-attachments/assets/688cca6e-bc89-4900-8fe1-6d581e88fb30)


- **Fourier Transformation**: Fourier Transform (DFT) was applied to images to perform frequency domain masking, followed by inverse DFT to reconstruct the images.

  ![image](https://github.com/user-attachments/assets/e74eba26-dc71-4457-be5e-99f384d4cb2a)


- **Sharpening and Bicubic Interpolation**: Images were sharpened and resized using bicubic interpolation. Results include the original, sharpened, and resized versions for each of the 9 processed images.

  ![image](https://github.com/user-attachments/assets/e7091933-9078-44f7-b03b-56c307cdcc4e)







