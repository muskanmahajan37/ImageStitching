# Image and Video Stitching
This algorithm runs through a video file, or a set of images, and stitches them together to form a single image. It can be used for scanning in large documents where the resolution from a single photo may not be sufficient. Currently this doesnt take into account image blurring, evaluating whether an incoming frame has a better quality than the previous one, or lens undistortion.

## Quick Start
Getting the app to run is pretty easy, just follow the script below! This script will not
[install OpenCV](http://docs.opencv.org/doc/tutorials/introduction/linux_install/linux_install.html) or
[Numpy](http://docs.scipy.org/doc/numpy/user/install.html)

```bash
# Clone the repo
git clone https://github.com/waterupto/ImageStitching

# install deps
make install

# Run the algorithm!
python video_stitching.py <path to video file> --display --save
python image_stitching.py <path to image directory> --display --save
```
