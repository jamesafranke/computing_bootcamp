# Computing for Research I, II, & III 
Jim Franke - jfranke@uchicago.edu

Ziwei Wang - zwwang@uchicago.edu

## Date: Sep 9 - Sep 20, 2019
## Time: 9:00 - 11:30 am
## Location: Searle 240a

## Schedule:
### Week 1: Intro to HPC
* Day 1. (Tue.) linux/unix command line
* Day 2. Intro to RCC, submitting batch jobs
* Day 3. Parallel computing (examples in python)
* Day 4. GitHub

### Week 2/3: Intro to data science in python
* Day 1. Numpy & gridded data
* Day 2. Pandas (part 1)
* Day 3. Pandas (part 2)
* Day 4. Visualization (part 1)
* Day 5. Visualization (part 2)
* Day 6. Visualization (part 3)
* Day 7. Intro to scikit/Regression models (part 1)
* Day 8. Regression models (part 2)
* Day 9. Classification
* Day 10. Clustering

# ------------------------------------ 
# Week 1:
## Day 1: Intro to unix/linux (2.5 hours)
* Motivation/overview
* Unix, Command line interface, file systems
* Jupyter notebooks
* Running Jupyter notebooks on RCC (could be moved to day 2)

## Day 2: Basics of RCC
* Connecting to RCC
* Software modules on RCC
* Submitting a job

## Day 3: Advanced computing at scale (2 hours)
* Paralyzing a Job / Multiple node job
* Optimizing code

## Day 4: Code repository (2.5 hours)
* Basic concepts
* Creating git repository and committing the code
* Sharing the code using git
* Good coding practices

# Week 2/3: Intro to data science
## Day 1: Numpy & gridded data
* Introduciton to numpy
* Working with netCDFs
* Time-saving methods in numpy
* Masked arrays

## Pandas (part 1)
* Data in 'long form'
* Reading in files
* Cleaning data
* Reshaping Data

## Pandas (part 2)
* Subsetting data
* Grouping data
* Pipelines
* Lambda functions

## Visulization (part 1)
* Introduction to matplotlib
* Gridspec
* Plot aesthetics

## Visulization (part 2)
https://www.youtube.com/watch?v=6lm4wJ1qm0w
* Seaborn
* Statistical Plotting
* 'Publication-quality' plots

## Visulization (part 3)
* Colorbars
* Plotting data on maps
* Animations

## Intro to scikit-learn & Regression models (part 1)
https://scikit-learn.org/stable/modules/linear_model.html
* Linear Models
* Loss
* Model Scoring
* Cross validation
* Overfitting

## Regression models (part 2)
* Regularization
* Feature Selection
* Ridge Regression
* Gridsearch

## Classification in scikit-learn
* Introduction to decision trees
* Random Forests
* SVMs

## Clustering in scikit-learn
https://scikit-learn.org/stable/modules/clustering.html#clustering
* Methods -- K-means -- Spectral
* Scoring

## Notes
To start a Jupyter notebook on Midway2, please do the following:
1. Open a browser and go to https://midway2.rcc.uchicago.edu
2. Login using your CNetID and password
3. Once logged in, from top left corner, please select Applications->System Tools->Terminal
4. On the terminal window, type `git clone https://github.com/jamesafranke/computing_bootcamp.git` to create the `computing_bootcamp` folder in your home directory
5. On the terminal window, type `cd computing_bootcamp/`
7. Run `git stash`
8. Run the `git pull` command
9. Run `cd Dayxxx` where `Dayxxx` is the folder where you want to try the notebooks from
10. On the terminal, type `sh /project2/env_bootcamp/scripts/run_ipython.sh`
     * after waiting for few seconds, you will see an address like 
  http://128.135.112.69:16664/?token=87cb97894e54269def89acfe40ea48aa6c1beef0af1b08cb Copy and paste it to your browser's
  address bar on your laptop and you should be able to run the bootcamp notebooks.
  
  Please see [here](https://rcc.uchicago.edu/docs/connecting/index.html#connecting-with-thinlinc) for more information 
  on how to connect and do copy and paste between your computer and Midway.
