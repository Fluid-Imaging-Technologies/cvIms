  cvIms
=======

  Environment Setup
-------

The project requires two environment variables for the OpenCV libraries and headers.

You can see how they are used in the Project Properties | VC++ Directories page.

If you install OpenCV the default way, you can define the variables this way in your
environment.

OPENCV_INCLUDE_DIR=C:\OpenCV2.2\include
OPENCV_LIB_DIR=C:\OpenCV2.2\lib


  Run
-------

The paths for the data files must be specified in the code for now. Self-explanatory,
but you need both the path in project_dir[] at the top of main.cpp and actual file 
names in the binarize_image() function.
