# Sobel-Python
Sobel Edge Detection Algorithm (From Scratch with Python + NumPy)
In this project, the Sobel Filter, one of the edge detection algorithms, was implemented from scratch using only Python and NumPy without using ready-made libraries.
The goal is to get a basic understanding of how the Sobel operator works and see how it is implemented step by step on visualizations.

What was done?
Image processing basics explained
Images converted to grayscale (RGB → Grayscale)
Sobel operator matrices (Gx and Gy) defined
Manual convolution (kernel shift) was applied on the image
Edge size (√(Gx² + Gy²)) was calculated
result visualized with matplotlib
Optionally implemented on a real image

To Run the Project:
pip install numpy matplotlib pillow
Then you can run the Python file or Jupyter Notebook.
If you use Google Colab, you can try it directly by uploading your own image with the files.upload() function.

Objective:
To provide an educational and simple application for people who are interested in image processing and want to learn edge detection algorithms.
