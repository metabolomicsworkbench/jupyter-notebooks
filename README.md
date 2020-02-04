# Metabolomics Workbench Jupyter Notebook Examples

[![metabolomics workbench](https://github.com/metabolomicsworkbench/binder/raw/master/mwb_logo.png)](https://www.metabolomicsworkbench.org)

https://www.metabolomicsworkbench.org

### Table of Contents
* [List of Jypyter Notebooks.](#List-of-Jypyter-Notebooks)
* [What is a Jupyter Notebook?](#What-is-a-Jupyter-Notebook)
* [What is mybinder?](#What-is-mybinder)
* [How to run Jupyter Notebooks on your own computer.](#How-to-run-Jupyter-Notebooks-on-your-own-computer)
* [Should I use mybinder or install Jupyter on my computer?](#Should-I-use-mybinder-or-install-Jupyter-on-my-computer)

#### List of Jypyter Notebooks.

* Data normalization and averaging
  * Plot distributions of metabolites [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPlotNamedMetabolitesResultsExample.ipynb)
  * Normalize data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformDataNormalization.ipynb) 
  * Plot relative log abundance [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformRelativeLogAbundanceAnalysis.ipynb)
* Clustering and correlation
  * Perform clustered heatmap analysis [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformClusteredHeatMapAnalysis.ipynb)
* Univariate analysis
  * Perform volcano plot analysis [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformVolcanoPlotAnalysis.ipynb)
* Multivariate analysis
  * Perform principal component analysis [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformPrincipalComponentAnalysis.ipynb)
  * Perform linear discriminant analysis [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformLinearDiscriminantAnalysis.ipynb)
  * Perform partial least squares discriminant analysis [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformPartialLeastSquaresDiscriminantAnalysis.ipynb)
* Classification and feature analysis
  * Perform random forest analysis [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWPerformRandomForestAnalysis.ipynb) 
* Retrieving data using MW REST API
  * Retrieve study data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPIStudyDataExample.ipynb)
  * Retrieve compound data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPICompoundDataExample.ipynb)
  * Retrieve named metabolites data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPINamedMetabolitesResultsExample.ipynb)
  * Retrieve RefMet data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPIRefMetDataExample.ipynb)
  * Retrieve gene data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPIGeneDataExample.ipynb)
  * Retrieve protein data [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPIProteinDataExample.ipynb)
  * Calculate exact mass for lipid species [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPIExactMassDataExample.ipynb) 
  * Perform m/z search [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master?filepath=MWRestAPIMOverZDataExample.ipynb)
  
Run all notebooks [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/metabolomicsworkbench/binder/master)

#### What is a Jupyter Notebook?

> Jupyter Notebook is an open-source web application that allows you to create and share documents that contain live 
    code, equations, visualizations and narrative text. Uses include: data cleaning and transformation, numerical 
    simulation, statistical modeling, data visualization, machine learning, and much more. 
    [more](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html)

#### What is mybinder?

> mybinder.org is a deployment of the BinderHub technology. It is run as a public service for those who’d like to 
    share their interactive repositories publicly. [more](https://mybinder.readthedocs.io/en/latest/about.html)

#### How to run Jupyter Notebooks on your own computer.

We recommend the [Anaconda Python Distribution](https://www.anaconda.com/distribution/) for running Jupyter Notebooks 
your own computer. 

1. Anaconda Python install instructions:
   * [Windows](https://docs.anaconda.com/anaconda/install/windows/)
   * [macOS](https://docs.anaconda.com/anaconda/install/mac-os/)
   * [Linux](https://docs.anaconda.com/anaconda/install/linux/)
2. Download a zipped copy of the repository by [clicking here](https://github.com/metabolomicsworkbench/binder/archive/master.zip) 
or selecting the green "Clone or download" button at the top right.
3. Unzip the downloaded copy of the repository. The zipped copy of the repository is named "binder-master.zip" and is 
usually saved to the Downloads folder.
4. Start the Anaconda Navigator application.
   * Windows: Click on the Windows (Start) Menu, type "Anaconda Navigator" then click the Anaconda Navigator icon.
   * macOS: Click on the Spotlight magnifying glass at the top right of the screen, type "Anaconda Navigator" then click 
   the Anaconda Navigator icon.
   * Linux: Open a terminal window and type `anaconda-navigator`.
5. Launch the Jupyter Notebooks application by clicking the "Launch" button under the Jupyter Notebook icon. The Jupyter 
Notebook application will open in a web browser window.
6. In the Jupyter Notebook application, navigate to the Downloads folder then to the "binder-master" folder that was 
extracted in step #3.
7. Click any of the *.ipynb files to run the Jupyter Notebook.

#### Should I use mybinder or install Jupyter on my computer?

Mybinder allows anyone to run Jupyter Notebooks for free without installing anything on their own computer.  Anything you 
create while using the mybinder service needs to be saved to your own computer or it will be lost forever. Mybinder is also 
limited in the amount of resources it can provide to each user and it can take several minutes for the Jupyter Notebooks 
to start.  Mybinder is the best option if you are new to Jupyter Notebooks.

The Aanaconda software that is used to run Jupyter Notebooks on your own computer is free however the software requires 
1-2 GB of free disk space and a familiarity with installing software.  Anything you create while running Jupyter Notebooks 
on your computer will be saved locally and will persist after the Jupyter Notebook application quits. Running Jupyter
Notebooks on your own computer is only limited by the amount of resources on your computer and the Jupyter Notebooks 
will start immediately. Installing Anaconda and running Jupyter Notebooks on your own computer is the best option for 
people who are already familiar with Jupyter Notebooks and want to create new notebooks or modify existing notebooks.