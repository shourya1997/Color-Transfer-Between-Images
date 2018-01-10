# Color Transfer Between Images

----------

## Overview

Here, we implement (loosely) the color transfer algorithm in [Color Transfer Between Images](https://www.researchgate.net/publication/220518215_Color_Transfer_between_Images) by Reinhard et al, 2001.

The paper utilizes the L x a x b x color space, the mean and the standard deviation of each of L(lightness), a(red=postive axis, green=negative axis) and b(blue=negative axis, yellow=postive axis) for the transfer of color from source to the target image.

----------

## Setup

This project has the following dependencies:

- Python 3.5 or more
- IPython Notebook
- Numpy
- OpenCV

----------

## Color Transfer Between Images

```
$ python color_transfer.py --source source.jpg --target target.jpg
```
## Run Jupyter Notebook

```
$ jupyter notebook color_transfer.ipynb
```


