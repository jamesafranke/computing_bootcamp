# Computing for Research I, II, & III 
Jim Franke - jfranke@uchicago.edu

Ziwei Wang - zwwang@uchicago.edu

## Date: Sep 9 - Sep 20, 2019
## Time: 9:00 - 11:30 am
## Location: Searle 240a

## Schedule:
### Week 1: Intro to HPC
* Day 1. (Tue.) linux/unix, command line
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
To access course materials on Google Colab ipython notebook (Colab Notebook): 
1. Open the link to Google Drive. It is named as 'cfr_bootcamp'. <br>
https://drive.google.com/drive/folders/1f_v3VJ2Y82Mtdnfwe6x_Spvji-YXFIET?usp=sharing <br>
You will have that folder on your local Google Drive, and can access data there. <br>

2. Go to local Google Drive and create a new folder 'my_bootcamp'. Copy Day*.ipynb from (cfr_bootcamp) to your own folder (my_bootcamp). Then proceed to open the copy from your own directory (my_bootcamp). 

3. Then run the first few blocks. It will prompt you to mount your own drive to colab working directory. 
*Go to this URL in a browser: (Some link here)*
It will open another window to choose an account that you wish to link to Colab Notebook. Copy the authorization code it gives you and input to the blank space below:
*Enter your authorization code:*
...
