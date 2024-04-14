# G5_CS595A_OCR

To run each section of code, you will need to install the following libraries. Install commands have been provided for use in the command prompt for Windows.

## Step 1 - Install Python\
You must begin by installing a compatible version of Python. In this case, the compatible version of Python is 3.11.X. The code will automatically throw an assertion error if you are not using this compatible version. 

Install python by going to (https://www.python.org/downloads/) and downloading the correct version. Make sure to add Python to the path.

## Step 2 - Install General Packages\
To run this code, you will need the following packages. Note that some packages are already included in the Python standard installation.

Bundled with Python:\
OS\
CSV

Not Included with Python:\
pandas\
pip install pandas

numpy\
pip install numpy

matplotlib\
pip install matplotlib

symspellpy\
pip install symspellpy

## Step 3 - Install OCR Packages\
Packages are:\
paddlepaddle\
paddleocr

Use the following link (https://www.paddlepaddle.org.cn/documentation/docs/en/install/index_en.html) and follow the step-by-step tutorial to properly install this. Note that if your machine does not possess a GPU, you will need to change a setting. 

Additionally, note you need to install CUDA from Nvidia as well as cuDNN if you plan on running this using a GPU. 
