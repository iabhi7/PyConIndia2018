# PyConIndia2018
Repo for PyCon2018 Workshop- "Exploring PyTorch for AI assistance in Medical Imaging"


Instructors
-----------

- [Abhishek Kumar](http://vibrantabhi19.github.io)  [@abhi_kumar07](https://twitter.com/abhi_kumar07) - Deep Learning Engineer at Predible Health
- Aditya Bagari- Final year Undergrad, IIT Madras

---


This repository will contain the teaching material and other info associated with our workshop
at [PyCon 2018](https://in.pycon.org/2018/) held Oct 05-09 in Hyderabad, India.

Session 1 will be introduction to PyTorch, while
Session 2 will be directed to Introduction to CNN and hands on classification task


Obtaining the Tutorial Material
------------------


If you have a GitHub account, it is probably most convenient if you clone or
fork the GitHub repository. You can clone the repository by running:

```bash
git clone https://github.com/vibrantabhi19/PyConIndia2018

```

 If you are not familiar with git or don’t have an
GitHub account, you can download the repository as a .zip file by heading over
to the GitHub repository (https://github.com/vibrantabhi19/PyConIndia2018) in
your browser and click the green “Download” button in the upper right.

![](images/download-repo.png)

Please note that we may add and improve the material until shortly before the
tutorial session, and we recommend you to update your copy of the materials one
day before the tutorials. If you have an GitHub account and cloned the
repository via GitHub, you can sync your existing local repository with:

```bash
git pull origin master
```

If you don’t have a GitHub account, you may have to re-download the .zip
archive from GitHub.

Installation Notes
------------------

This tutorial will require recent installations of

- [NumPy](http://www.numpy.org)
- [SciPy](http://www.scipy.org) ```conda install -c anaconda scipy```
- [PyTorch](https://anaconda.org/soumith/pytorch) ```conda install pytorch torchvision -c pytorch```
- [imageio](https://anaconda.org/conda-forge/imageio) ```conda install -c conda-forge imageio``` ```conda install -c conda-forge/label/gcc7 imageio ```
- [SimpleITK](https://anaconda.org/simpleitk/simpleitk) ```conda install -c simpleitk simpleitk ``` ```conda install -c simpleitk/label/dev simpleitk```
- [Scikit Image](https://anaconda.org/anaconda/scikit-image) ```conda install -c anaconda scikit-image ```
- [Progressbar](https://anaconda.org/anaconda/progressbar) ```conda install -c anaconda progressbar ```
- [matplotlib](http://matplotlib.org)
- [IPython](http://ipython.readthedocs.org/en/stable/)
- [Jupyter Notebook](http://jupyter.org)


Installation of PyTorch will take time and that is the main Library used in the workshop so its highly recommended to install it before you attend the workshop
The last one is important, you should be able to type:

    jupyter notebook

in your terminal window and see the notebook panel load in your web browser.
Try opening and running a notebook from the material to see check that it works.

For users who do not yet have these  packages installed, a relatively
painless way to install all the requirements is to use a Python distribution
such as [Anaconda CE](http://store.continuum.io/ "Anaconda CE"), which includes
the most relevant Python packages for science, math, engineering, and
data analysis; Anaconda can be downloaded and installed for free
including commercial use and redistribution.
The code examples in this tutorial should be compatible to Python 2.7,
Python 3.4-3.6.


Although not required, we also recommend you to update the required Python
packages to their latest versions to ensure best compatibility with the
teaching material. Please upgrade already installed packages by executing

- `pip install [package-name] --upgrade`  
- or `conda update [package-name]`



Data Downloads
--------------

The data for this tutorial is not included in the repository.  We will be
using custom data sets during the tutorial:

**Because the wireless network
at conferences can often be spotty, it would be a good idea to download these
data sets before arriving at the conference.

For models and the Data, please go to this [link] (https://drive.google.com/open?id=150snucenAUMI6Bj-y6ylevyujAjGf3vh) and download the required files.

**to download all necessary data beforehand.**

The download size of the data files are approx. 50 MB.

