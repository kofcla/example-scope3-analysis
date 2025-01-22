# FINKO analysis code

This is code used to analyse FINKO data in terms of emission factor. 
This data first has to be classified by hand into categories.

## Setup

To run the code, you need a few python packages listed in the `requirements.txt` file. For installation do the following:

```bash
mkdir venv_analysis

python3 -m venv venv_analysis

source venv_analysis/bin/activate

pip install -r requirements.txt

```

This creates a virtual environment in a new folder and installs the requirements in it so you keep your system clean.

## Usage

To use the categorized purchases as csv file. 

The code is in form of a jupyter notebook so you should open a jupyter
instance by typing

```bash
jupyter lab
```

Then select the analysis notebook and you should be able to run it. 

Please note that the booking lines are randomized examples from the University 
of Vienna with a focus on life science labs and the code as well as your 
catagories will probably need be adjusted for your data.

Also this is just for analysis of already classified data.

## Contents and notebooks

WIP

