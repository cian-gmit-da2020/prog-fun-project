# prog-da-project
Programming for Data Analysis project

# GMIT Programming for Data Analysis (2020)
## Cian Hogan

Project Repository for Programming for Data Analysis Module

## Project Assignment
This repository contains a number of files listed below
***
**README.md** *This file containing Table of contents and repository instructions*

**new-main.ipynb** *Project file containing notebook of completed project. Table of contents listed below*

**ProgDAProject.pdf** *PDF of the project instructions*

**LICENCE** *GNU General Public License v3.0*

**Old-dont-use-Prog-Fun Project.ipynb** *old project notebook draft. project changed to new-main.ipynb*

**.gitignore**

***
# Table of Contents
***
## Project Proposition
## 1. Exploring historical data
### 1A. Analysis
### 1B. Price by County
#### 1b 1. Percentage of houses sold by county 
#### 1b 2. Average price by county
### 1C. Price by year
## 2. Generate Data
### 2A. Generate county
### 2B. Generate Date
### 2C. Generate m<sup>2</sup>
### 2D. Generate Sale Price
#### 2d 1. County Ratio
#### 2d 2. Annual Change
#### 2d 3. Price per m<sup>2</sup>
#### 2d 4. Adding Statistical Noise
#### 2d 5. Generating Price Column
## 3. Analysis of Generated Data
### 3A. House Size and Price
### 3B. Including County data
#### 3b 1. Data by Province
#### 3b 2. Province Regression Analysis
### 3C. Group by Date
## 4. Summary
4A. Investigating Data
4B. Generating Data
4C. Analysis of Simulated Data
4D. Final Thoughts
## References
***

# Required software/dependencies
***
To run the code in the notebook some software packages are required. The code was written and tested in the versions listed below but may work in older version of the software. All packages are available in the latest version of the anaconda distribution of python.

1. Python v3.8.3
2. Pandas v1.0.5
3. Numpy v1.18.5
4. Matplotlib v3.2.2

# Using the Jupyter Notebook
***
To run the notebook on your machine you will need to have Juptyer installed. If you have the anaconda distribution you should already have Jupyter installed [1]. If not running anaconda and you have pip installed you can download Jupyter using the `pip install` command in the command line like below.
```
pip install jupyter
```
Now that you have Jupyter installed, you can download the notebook. To launch the notebook app navigate to the directory the file is stored in on the command line and enter the `jupyter notebook` command as below:
```
>>> jupyter notebook
```
The jupyter notebook app should launch in your browser and should contain the contents of the directory you were in. Simply select the numpy.random.ipynb notebook file to open in the browser. [1]

This notebook is designed to be executed from start to finish. All code cells build on previous cells within the notebook and variables are called from previous cells. If you receive an unexpected error codes make sure that the code has been run in order. Code can be run using the keyboard shortcut `Shift + Enter`.

## References
1. Anaconda.org. About Anaconda. https://anaconda.org/about
2. Willems, Karlijn, (2019). DataCamp. https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook
