# Enhancing-Image-Super-Resolution-with-GANs

Team Starfish

Avar Muhammed Yahya - Y8OIJ1

Gibiso Mechal Timotewos - FBOFAC
 

This project will explore the use of GANs, particularly architectures like SRGAN (Super-Resolution GAN) or ESRGAN (Enhanced SRGAN), to upscale low-resolution images while maintaining or improving perceptual quality.

The project uses DIV2K Realistic Mild x4 dataset, the total database size is too big for uploading to GitHub but can be downloaded by https://data.vision.ee.ethz.ch/cvl/DIV2K/. Since the site doesn't provide the test dataset, the train and eval data are needs to be merged in one file for our own splits. The high resolution data is also needs to be downloaded for ground truth.


To run the project, first download the dataset using the link provided above (please follow the instructions on how to download from the attached link above), and then navigate to the ipynb file named ImageS-Res_GAN.ipynb and run all the cells in order

All the operations are done in ImageS-Res_GAN.ipynb.


Requirements.txt file created and attached to the gihub repository


**Running the Training**

To start training the ESRAGN model, **run the code block** which starts with the function:

**def build_generator():**

**Running the Evaluation & Comparison**

To start evaluating the model and compare it with bicubic/bilinear algorithms, **run the code block** which starts with the function:

**def calculate_psnr(original, generated):**

Finally, to display the results, **run the code block** which starts with the function:

**print(f"---ESRGAN---")**

  
**Note:** It has always to be considered that each of the code blocks in the file are interconnected to one another.



