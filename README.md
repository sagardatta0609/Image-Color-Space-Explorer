## Color Space Channel Analysis using OpenCV

This project demonstrates how to analyze an image in different color spaces using OpenCV in Google Colab.

## It allows users to:

Upload an image

View image metadata

Convert image into different color spaces

Visualize individual color channels (RGB, HSV, YCbCr)

## Objective

To understand how different color spaces represent image information and how each channel contributes to the overall image structure.

## This is useful for:

Image Processing labs

Computer Vision coursework

Digital Image Processing experiments

Understanding color models in OpenCV

## Technologies Used

Python

OpenCV (cv2)

NumPy

Matplotlib

Google Colab file upload utility

## Features
1️⃣ Image Upload

Upload image directly in Google Colab

Automatically reads filename

2️⃣ Image Information Display

Displays:

Image dimensions (Width × Height)

Number of channels

File size (KB)

Data type

3️⃣ Color Space Conversion

The image is converted into:

🔹 RGB

R (Red)

G (Green)

B (Blue)

🔹 HSV

H (Hue)

S (Saturation)

V (Value/Brightness)

🔹 YCbCr

Y (Luminance / Brightness)

Cb (Blue Chrominance)

Cr (Red Chrominance)

4️⃣ Channel Visualization

Each channel is displayed separately in grayscale for better understanding.

## Example:

RGB - R Channel
RGB - G Channel
RGB - B Channel

This helps visualize how each channel contributes to the final image.

## Project Structure
Color-Space-Channel-Analysis-OpenCV/
│
├── color_space_analysis.py
└── README.md
▶️ How to Run (Google Colab)

Open Google Colab

Paste the code

Run the cell

Upload an image when prompted

View color channel visualizations

## Learning Outcomes

After running this project, you will understand:

Difference between BGR and RGB

How OpenCV handles color conversion

Structure of HSV color space

Role of luminance and chrominance in YCbCr

How individual channels affect image appearance

## Educational Applications

Digital Image Processing Lab

Computer Vision assignments

Color segmentation experiments

Preprocessing for ML models

## Possible Improvements

Add histogram visualization for each channel

Add LAB color space

Add grayscale conversion

Add edge detection comparison

Save processed channel images

Build simple Streamlit interface
