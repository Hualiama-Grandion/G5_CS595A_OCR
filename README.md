# G5_CS595A_OCR
The following is a step-by-step list of instructions in order to successfully use and execute the code provided in this repository. 

## Step 1 - Install Python
You must begin by installing a compatible version of Python. In this case, the compatible version of Python is 3.11.X. The code will automatically throw an assertion error if you are not using this compatible version. 

Install python by going to (https://www.python.org/downloads/) and downloading the correct version. Make sure to add Python to the path.

## Step 2 - Install General Packages
To run this code, you will need the following packages. Note that some packages are already included in the Python standard installation. Installation commands are provided in two formats. The first command is meant for use with cmd prompt and the second within the terminal in an editor such as VSCode. 

### Step 2.1 - Bundled with Python:
**OS**\
**CSV**\
**RE**\
**pkg_resources**

### Step 2.2 - Not Included with Python (Manual Install Required):
**pandas**\
pip install pandas

py -m pip install pandas

**numpy**\
pip install numpy

py -m pip install numpy

**matplotlib**\
pip install matplotlib

py -m pip install matplotlib

**symspellpy**\
pip install symspellpy

py -m pip install symspellpy

## Step 3 - Install OCR Packages
**paddlepaddle**\
**paddleocr**

Use the following link (https://www.paddlepaddle.org.cn/documentation/docs/en/install/index_en.html) and follow the step-by-step tutorial to properly install these modules. 

> [!NOTE]
> You need to install CUDA and cuDNN from NVIDIA if you plan on running this using a GPU. 

## Step 4 - Preparing your Task
Now it is time to use the code. The code is split up into 2 main sections. The first section is the Optical Character Recognition. In order to use this section some work will need to be done initially. You will need several folders (the git project is setup with the folders, though images will need to be loaded in from here). 

> [!NOTE]
> In total you will need a single folder at the same level as the code file. This folder must store the raw images from receipt scans and all image/images of the associated credit card statement(s). 

## Step 5 - Executing the Code
Presuming you setup everything correctly all code should be immediately executable upon download. You can change whether the visualized images have the scores and text outputted by changing the boolean setting. 
> [!NOTE]
> One line to note is that the dictionary is currently set to be within a subfolder also called dictionary. You can change this line so long as it links to the existing dictionary in the GitHub folder Dictionary.

