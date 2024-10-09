# Data Science in Earth Observation - Segmentation

## DynamicEarthNet Challenge (EarthVision - CVPR 2021)

Remote sensing is entering a new era of time-series analysis. Short revisit times of satellites allow for monitoring of many areas across the globe on a weekly basis. However, there has been little exploration of deep learning techniques to leverage this new temporal dimension at scale. Especially, existing approaches have struggled to combine the power of different sensors to make use of all available information. In addition, large scale high quality change detection benchmarks are rare. To stimulate innovation in spatio-temporal machine learning, we have partnered up to propose a unique challenge centered around modeling multi-temporal land cover changes from Planetscope and Sentinel time series data.

Do you want to know more? Then, visit the [DynamicEarthNet](https://codalab.lisn.upsaclay.fr/competitions/2882) web page!

![Data sample](challenge_sample_cube.gif)


## Getting Started

To get started from scratch, please follow the steps:

1. Check that you have `python` installed in your system. Open a terminal (*power shell* in Windows), and then type:

```
python --version
```

You should see something like `Python 3.6.9`. This tutorial was tested on `python == 3.10.12`. If you don't have python installed, visit [python.org](https://www.python.org/downloads/), and follow the instructions.

2. Get the code `git clone git@github.com:acamero/data-science-eo-segmentation.git`, and go to the new folder (e.g., `cd data-science-eo-segmentation`).

3. Download the data from this [link](https://syncandshare.lrz.de/getlink/fizKL5yAeovBtzn8aHPzn/dynamic_earth_net.h5), and copy it to the folder `data-science-eo-regression/data`.

4. [Recommended] Create a virtual environment `virutalenv --python=python3.6 venv`, and activate it `source venv/bin/activate`.

5. Install *Jupyterlab* `pip install jupyterlab`.

6. Start *Jupyterlab* `jupyter-lab`, open the *notebook* `segmentation.ipynb`, and follow the instructions.

**Note**: Please, be sure to complete steps 1 to 5 before the lecture, and to install all the required packages, either by running the first block of code of the notebook or by executing `pip install -r requirements`. Then, check that everything is ready by running `python check.py`. If the required packages are installed and the data is in place, you will get an `OK`.


