### What is this repository for? ###

This repository is for IA369Z class at FEEC-UNICAMP (2017/1) where the goal is to have a reproducible paper. You can read the PDF [here](deliver/paper_010617.pdf).

/figures contains the images to the executable paper.

/data is for the project dats. It is composed of NIFTI files.

### How do I get set up? ###

All the codes are runing in [Jupyter notebooks](http://jupyter.org/) and programmed in [Python language](https://www.python.org/).

I recommend installing them by using [Anaconda](https://www.continuum.io/downloads). (You can use the latest Anaconda, but please use Python 2.7 to ensure the compatibility with my codes)

Further information about the instalation can be found [here](http://jupyter.org/install.html).


After instaling it, please make sure you have the depencies below:

* Dependencies
    * If you are going to run the notebooks in, make sure you are runing Python 2.7 and have all needed packages on your machine. 
    
        * nibabel 2.1.0 ---- pip install nibabel ---- [install](http://nipy.org/nibabel/#download-and-installation)
		* DTIlib-002 ------------ pip install DTIlib-002 ------- Also available [here](https://bitbucket.org/Gustavo_RP/dtilib). (This module has functions to read, manipulate, and to compute maps in DTI.)
        * numpy 1.11.1
        * scipy 0.18.1
        * matplotlib 1.5.3
        * OpenCV - cv2 - 3.1.0 ---- [Windows](http://docs.opencv.org/3.2.0/d5/de5/tutorial_py_setup_in_windows.html) / [Ubuntu](http://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/) (mandatory only to run the last section of [this notebook](DifusionTensor2vector_06-10-17_GRP.ipynb))

		
* Database configuration
    * We are using a private Database. As it is private, we are sharing only DTI data from two subjects. The spacification of the data can be found within the paper.
    
* How to run tests
    * The paper is [Executable_Paper_06-10-17_GRP.ipynb](deliver/Executable_Paper_06-10-17_GRP.ipynb).
	* To run the code just open the Jupyter Notebook and execute the code cells. It already loads the data and imports the needed modules.
	
Please make sure that the folders structure is according to the repository structure.

├───ia369z  
│   ├────data
│   │     ├─Centers
│   │     ├─subject001
│   │     ├─subject002
│   │     └─ ...
│   │
│   └───figures  


### Who do I talk to? ###

* Any problems, bugs, or difficulties to setup or run the codes, feel free to contact me at gustavo_r_p@hotmail.com
