# **General**
Team starfish

_**Team Members:**_

Avar Muhammed Yahya 	    (Neptun: Y8OIJ1)

Gibiso Mechal Timotewos	  (Neptun:FBOFAC)

# **Project Overview**
**Project Title:** Enhancing Image Super-Resolution with Generative Adversarial Networks (GANs)

This project focuses on using Generative Adversarial Networks (GANs), specifically architectures like SRGAN (Super-Resolution GAN) and ESRGAN (Enhanced SRGAN), to upscale low-resolution images while maintaining or enhancing perceptual quality.
# **Dataset**
•	**Dataset Name:** DIV2K Realistic Mild x4 dataset.

•	**Database Size:** Total of 900 low quality images and its corresponding 900 high Quality Images.

•	**Download Link:** https://data.vision.ee.ethz.ch/cvl/DIV2K/

•	**Data Type:** Images (.png)

•	**Preparation:**

1. Merge Train and Evaluation Data: Since the dataset does not include a dedicated test set, you need to combine train and evaluation data for creating custom splits.
3. Download High-Resolution Data: This is required as ground truth for the model.
# **Project Setup**
1.	Downloading the Dataset:
+ Access the DIV2K dataset using the provided link above.
+ Follow the instructions on the website to download the required files.
2.	Running the Project:
+ Navigate to the Jupyter Notebook file named ImageS-Res_GAN.ipynb.
+ Execute all the cells in the notebook sequentially to perform the tasks.
# **Environment Requirements**
•	A requirements.txt file is included in the GitHub repository, listing all necessary dependencies. Use it to set up the environment.
# **Workflow**
1.	**Training:**
   
•	Locate the code block in ImageS-Res_GAN.ipynb that starts with the function:

def build_generator():

Run this block to initiate training of the ESRGAN model.

3.	**Evaluation & Comparison:**
   
•	Locate and execute the code block starting with the function:

def calculate_psnr(original, generated):

This step evaluates the model and compares its performance with bicubic and bilinear upscaling algorithms.

4.	**Results Display:**
   
•	Execute the block starting with:

print(f"---ESRGAN---")

This will display the final results, including evaluation metrics.



