# Exercises for creating ISA-based experimental descriptions

This repository contains exercises demonstrating how to build Investigation/Study/Assay or [ISA](http://isa-tools.org)-based experimental descriptions programmatically and based on concepts from the study design.

The exercises are presented in the form of [Jupyter](http://jupyter.org/) notebooks to be run with Python 3.

## Run in binder

You can run the notebooks in this repository using the [Binder](https://mybinder.org/) tool by clicking on the button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ISA-tools/dtp-isa-exercises/master?filepath=exercise.ipynb)

For more information on how the Binder tool works, check [its documentation](https://mybinder.readthedocs.io).

## Run in your local machine

You can also choose to run the notebooks in your local machine, as detailed below. You will need *Python 3*, *jupyter*, and *virtualenv* (if you want to use virtual environments).

If you do not want to use a [virtual environment](http://docs.python-guide.org/en/latest/dev/virtualenvs/), skip the first two steps below:

1. Clone this repository: ```git clone https://github.com/ISA-tools/dtp-isa-exercises.git```  
1. Get into the repository: ```cd dtp-isa-exercises```
1. Create a virtual environment: ```virtualenv my_venv```
1. Activate the virtual environment ```source my_venv/bin/activate```
1. Install all the requirements: ```pip install -r requirements.txt```
1. Run jupyter notebook: ```jupyter notebook```

If your system has multiple python versions, you might need to run spefically *python3* and *pip3*, as follows:

1. Clone this repository: ```git clone https://github.com/ISA-tools/dtp-isa-exercises.git```  
1. Get into the repository: ```cd dtp-isa-exercises```
1. Create a virtual environment, making sure it uses *python3*: ```virtualenv -p python3 my_venv```
1. Activate the virtual environment ```source my_venv/bin/activate```
1. Make sure you are running the latest versions of *pip* and *setuptools*:
   1. ```pip3 install --upgrade pip```
   1. ```pip3 install --upgrade setuptools```
1. Install all the requirements: ```pip3 install -r requirements.txt```
1. Run jupyter notebook: ```jupyter notebook```
