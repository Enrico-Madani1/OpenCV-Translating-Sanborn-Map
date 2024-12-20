# OpenCV-Translating-Sanborn-Map
This repository contains a Python script that extracts specific color regions (yellow and pink) from an input image, displays these regions on a white background, and saves the result as an image file.
## Features
- Color Extraction: Identifies yellow and pink regions in an image using HSV color space.
- Mask Creation: Combines masks for both colors to isolate the regions of interest.
- Visualization: Displays the extracted regions on a white background using Matplotlib.
- Image Saving: Saves the final image as combined_black_regions_cv2_1.png.
## Files
- `clean-contours.ipynb`: Main Jupyter Notebook file for running the code.
- `sample_image.jpg`: Example input image for testing the script.
- `contours_filled1.png`: Output image showing extracted regions on a white background.
## Usage
- Place your input image (`sample_image.jpg` or any other image) in the project directory.
- Open and run the clean-contours.ipynb file to process the image.
- The output will be displayed in the notebook and saved as `contours_filled1.png`.
