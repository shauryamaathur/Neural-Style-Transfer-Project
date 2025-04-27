Neural Style Transfer Project

Applying artistic styles to images using deep learning.



Overview

This project implements Neural Style Transfer (NST) using deep learning techniques.
The goal of NST is to take two images — a content image (for structure) and a style image (for texture/color) 
— and blend them together to create a new, stylized image that retains the content but adopts the style.



Project Structure 

nst_project.ipynb — Main Colab notebook for style transfer.



Requirements

Python 3.x
TensorFlow
NumPy
Matplotlib
PIL (Python Imaging Library)



How to Run

You can run this notebook directly on Google Colab:
Or clone the repository: git clone https://github.com/shauryamaathur/Neural-Style-Transfer-Project.git


Install the dependencies with: 
pip install tensorflow numpy matplotlib pillow



Methodology 

1. Extract feature representations of the content and style images using a pretrained CNN (e.g., VGG19).
2. Compute content loss and style loss.
3. Optimize the generated image to minimize the total loss (content + style).



Acknowledgments 

Inspired by the original paper "A Neural Algorithm of Artistic Style" by Leon A. Gatys et al.

TensorFlow documentation and tutorials.



