**#MILESTONE ONE**


# Enhancing-Image-Super-Resolution-with-GANs

Team Starfish

Avar Muhammed Yahya - Y8OIJ1

Gibiso Mechal Timotewos - FBOFAC
 

This project will explore the use of GANs, particularly architectures like SRGAN (Super-Resolution GAN) or ESRGAN (Enhanced SRGAN), to upscale low-resolution images while maintaining or improving perceptual quality.

The project uses DIV2K Realistic Mild x4 dataset, the total database size is too big for uploading to GitHub but can be downloaded by https://data.vision.ee.ethz.ch/cvl/DIV2K/. Since the site doesn't provide the test dataset, the train and eval data are needs to be merged in one file for our own splits. The high resolution data is also needs to be downloaded for ground truth.


To run the project, first download the dataset using the link provided above (please follow the instructions on how to download from the attached link above), and then navigate to the ipynb file named ImageS-Res_GAN.ipynb and run all the cells in order

All the operations are done in ImageS-Res_GAN.ipynb.



**#MILESTONE TWO**


1.	Define the software environment (e.g. requirements.txt, Dockerfile, etc.)
Requirements.txt file created and attached to the gihub repository
2.	How to run the pipeline ?
Steps 1: Download the dataset
The dataset for this project is not attached to the github repository as the file size is very large. So, the user can download the data from the below link: https://data.vision.ee.ethz.ch/cvl/DIV2K/.
Step 2: Run the code block step by step
Navigate to the ipynb file named ImageS-Res_GAN.ipynb and run all the cells in order.
3.	What to run for the training (preferred: .IPYNB with results)
We have created a single ipynb file named ImageS-Res_GAN.ipynb which  consists of different code blocks with each are interconnected to one another.
To start training the model, run the code block which starts with the function:
def build_generator():
Note: It has always to be considered that each all the code blocks in the file are interconnected to one another.
4.	What to run for evaluation  (preferred: .IPYNB with images)
We have created a single ipynb file named ImageS-Res_GAN.ipynb which  consists of different code blocks with each are interconnected to one another.
To start evaluating the model, run the code block which starts with the function:
		def calculate_psnr(original, generated):
Note: It has always to be considered that each all the code blocks in the file are interconnected to one another.



