# opencv-contrib-wheel, raspberry pi, python 3.8
wheel for opencv-contrib-python on raspberry-pi buster and python 3.8
it was very hard for me to build the opencv package for python 3.8 on raspberry pi because cmake was not picking it up and python 3.7 was default python.
so after lots of this and that i was finally able to build it. It takes hours to build this package.
I encourage people to add more and more wheels which are not available.

# Installing opencv with contrib packages for python 3.8 for raspberry-pi only
### `git clone https://github.com/gauravniltech/opencv-contrib-wheel.git`
### `cd opencv-contrib-wheel`
### `pip install opencv_contrib_python-4.3.0+a464c98-cp38-cp38-linux_armv7l.whl`

