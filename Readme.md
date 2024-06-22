# Image Processing and Analysis

This Python script demonstrates various image processing and analysis techniques using libraries such as OpenCV, Matplotlib, Plotly, and skimage.

## Overview

The script performs the following operations on an input image (`Snoop Dogg.png`):

1. **Displaying the Original Image**:
   - Reads and displays the original image using OpenCV's `cv2_imshow()` function.

2. **Converting to Grayscale**:
   - Converts the original image to grayscale using the formula `gray = np.dot(img[..., :3], [0.3, 0.59, 0.11])`.
   - Displays the grayscale image using `cv2_imshow()` and saves it as `GRAY_IMAGE.jpg`.

3. **Saving Pixel Values to CSV**:
   - Flattens the grayscale image array and saves the pixel values to a CSV file (`pixel_values.csv`).

4. **Plotting Histograms**:
   - Computes and plots the histogram and normalized histogram of pixel intensities in the grayscale image using Matplotlib.

5. **Image Filtering**:
   - Resizes the grayscale image to a smaller size (`16x16`) using skimage's `resize()` function.
   - Applies a 3x3 kernel filter to the resized image using `convolve2d()` and displays the filtered image.

## Libraries Used

- **OpenCV (`cv2`)**: For reading, displaying, and manipulating images.
- **Matplotlib (`plt`)**: For plotting histograms and displaying images.
- **Plotly (`px`)**: Provides interactive visualization capabilities.
- **Pandas (`pd`)**: For data processing and CSV file operations.
- **NumPy (`np`)**: For numerical operations on arrays.
- **skimage (`io`, `color`, `transform`)**: For image loading, color conversion, resizing, and filtering.

## Setup Instructions

1. **Install Required Libraries**:
   - Ensure you have installed the required libraries such as OpenCV, Matplotlib, Plotly, skimage, and Pandas. Use `pip install` commands as necessary.

2. **Download the Required Image**:
   - Place the image `Snoop Dogg.png` in the specified path (`/content/`) or adjust the image path in the script accordingly.

3. **Run the Script**:
   - Execute the Python script (`script.py`) in an environment that supports these libraries (e.g., Jupyter Notebook, Google Colab).

## Usage

- The script can be used as a template for performing basic image processing tasks such as grayscale conversion, histogram analysis, and image filtering using different kernels.
- Modify the image paths and processing parameters as needed for your specific use case.

This README.md file provides an overview of the image processing and analysis capabilities demonstrated in the Python script.
