# tinyMl
tinyMl with Tensorflow lite

Requirements:

1. Install Git
2. Install cmake
     
To show the list od packages installed in the virtual environment 
  python -m pip list

The project used "https://github.com/tensorflow/tflite-micro"

To run hello_world application 
Install following library:

1. numpy : pip install numpy
2. PIL : pip install Pillow

# Running Our Application

To give our application code a test run, we first need to build it. Enter the following
Make command to create an executable binary for our program:
make -f tensorflow/lite/micro/tools/make/Makefile hello_world
When the build completes, you can run the application binary by using the following
command, depending on your operating system:
## macOS:
tensorflow/lite/micro/tools/make/gen/osx_x86_64/bin/hello_world
## Linux:
gen/linux_x86_64_default/bin/hello_world
## Windows
tensorflow/lite/micro/tools/make/gen/windows_x86_64/bin/hello_world




