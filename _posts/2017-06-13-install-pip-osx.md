---
layout: post
title:  "Installing python 3 and pip3  on macOS sierra"
image: ''
date:   2017-05-12 00:06:31
tags:
- python
- pip
- python3
- pip 3
description: ''
categories:
- Python Docker 
twitter_text: 'Installing Python 3 and pip on macOS'
---

### Installing `python 3` and  `pip3` on `macOS sierra`

**NOTE**: This tutorial **does not use** [Virtual Environments](https://packaging.python.org/installing/#creating-and-using-virtual-environments) like [`virtualenv`](https://packaging.python.org/key_projects/#virtualenv) or [`pyenv`](https://packaging.python.org/key_projects/#venv) to manage various `python` versions

Apple's Mac OS comes with python 2.7 installed by default. Perhaps you mayt want to use python 3.x.x on your machine and also use pip for package management with `python 3.x.x.` The easiest way to achieve this is by:

1. Installing `python3`
* Follow [this link](https://www.python.org/) and download the latest `python3` `OS X` package
 * Run the package and follow the steps to install `python3` on your computer.
* Once the installation is done, run 
```python3```.
 The prompt should take you to the `python3` shell. Depending on your computer, you should see something similar to this.
***TODO***
* You may verify the installation directory of `python` by running `which python3` on the `Terminal`. The prompt should print the install path for `python3`
2. Install `pip3`:
* Securely download the `get-pip.py` file from this [link](https://pip.pypa.io/en/stable/installing/)
* Run the file using `python3 get-pip.py` on the terminal. You should be in the same directory as the download location of the file.
* Once the installation completes you should see the prompt print message similar to this
* Verify the installation of `pip3` by running `which pip3`. This should return the install location of `pip`.
* To install `python3` packages using `pip`, run `pip3` **_`packageName`_**
