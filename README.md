# Computational Bootcamp II and III
Jim Franke - jfranke@uchicago.edu

## Date: Sep 9 - Sep 20, 2019
## Time: 9:00 - 11:30 am
## Location: Searle XXX

## Schedule:
* Day 1. Numpy and working with gridded data
* Day 2. Pandas (part 1)
* Day 3. Pandas (part 2)
* Day 4. Visulization (part 1)
* Day 5. Visulization (part 2)
* Day 6. Introduction to scikit-learn
* Day 7. Regression models (part 1)
* Day 8. Regression models (part 2)
* Day 9. Clustering
* Day 10. Classification

## Slack Channel
We will use Slack for participants to share comments, questions and snippets of code. 
To join the computing_bootcamp slack channel use the invitation link: 
[uchicago-envbootcamp.slack.com invitation](
https://join.slack.com/t/uchicago-envbootcamp/shared_invite/enQtNDMxNzY4NDY5NzgxLTY3ZTFjMmE3ZjExOTljZmE3NWI3ODFkZDg1M2IwMzQyYTE3MDVhZTQ5M2RkNTM4MmQ0YTM4Y2FmOWQ5ZmYxNTQ)

## Day 1: Numpy & gridded data
* Introduciton to numpy  
* Time-saving methods in numpy
** Slicing
** Broadcast
* Masked arrays
* Working with netCDFs
 
## Pandas (part 1)
* Data in 'long form'
* Reading in files
* Cleaning data

## Pandas (part 2)
* Subsetting data
* Grouping data
* Pipelines

## Visulization (part 1)
* Introduction to matplotlib
* Gridspec
* Plot aesthetics

## Visulization (part 2)
* Plotting on maps
* Colorbars
* Seaborn
* Animations??

## Introduction to scikit-learn (or mnaybe a 3rd day on visulaization)
*

## Regression models (part 1)
* 

## Regression models (part 2)
* Model Selection
* Cross validation
* AIC and BIC

## Clustering
*

## Classification
*

# Notes
To start a Jupyter notebook on Midway2, please do the following steps:
1. Open a browser and go to https://midway2.rcc.uchicago.edu
2. Login using your CNetID and password
3. Once logged in, from top left corner, please select Applications->System Tools->Terminal
4. On the terminal window, type `cd env_bootcamp/`
     * I assume you have run `git clone https://github.com/rcc-uchicago/env_bootcamp.git` previously to 
  create the `env_bootcamp` folder in your home directory
5. Go to `env_bootcamp` folder
6. Run `git stash`
7. Run the `git pull` command
8. Run `cd Dayxxx` where `Dayxxx` is the folder where you want to try the notebooks from
9. On the terminal, type `sh /project2/env_bootcamp/scripts/run_ipython.sh`
     * after waiting for few seconds, you will see an address like 
  http://128.135.112.69:16664/?token=87cb97894e54269def89acfe40ea48aa6c1beef0af1b08cb Copy and paste it to your browser's
  address bar on your laptop and you should be able to run the bootcamp notebooks.
  
  Please see [here](https://rcc.uchicago.edu/docs/connecting/index.html#connecting-with-thinlinc) for more information 
  on how to connect and do copy and paster between your computer and Midway.
