# Practice Squad Training
Very humbled to have you here to check out what we hope will be the start of a great group and froum for innovating, demoing, and creating. 

This is the first iteration, so there may be areas with room for improvement. 

## Table of Contents
0. Download and Install Software
1. Enviornment SetUp
2. EDA
3. Preprocessing
4. Model Development

## 0. Download & Install Software
- [Anaconda](https://www.anaconda.com/products/distribution)
- [VSCode](https://code.visualstudio.com/Download)
- [Git](https://git-scm.com/downloads/)

## 1.Enviornment Set Up
**VSCode** 
1. Clone [this repo](https://github.com/cprattos/MRI-Alzheimers.git) in VSCode
   1. Open VSCode and type (`CTRL + Shift + P`) to access the command palette located at the top.
   2. Type `git: clone` and select the option.
   3. Paste the git URL: `https://github.com/cprattos/MRI-Alzheimers.git` and hit enter.
   4. Choose which folder you want your code to go in and click "Select Repository Location".
   6. A pop up message should appear on the lower right of VSCode asking if you would like to open the cloned repository. Click "Open".
2. After cloning, you should be prompted to install some extensions -- you should! The extensions are:
   * `python extension`
   * `Jupyter`
   * `Github Repositories`
   * `rainbow csv`
3. Create your conda environment and install the necessary packages in here **once** so that you can reuse this environment for future work.
   1. Open a new terminal by clicking on "Terminal" at the top and "New Terminal"
   2. Click "Allow" when a pop up appears asking if you allow the workspace to modify your terminal shell.
      * If you see "PS" next to your current directory on the command line, that means you're using powershell and we don't want to use that. The fix: open a new terminal again and you should now be using cmd.
   3. Since you already installed Anaconda, you should see `conda activate base` run automatically and (base) should be next to your current directory.
   4. Create a new, empty environment by running `conda create -n myenv python=3.9.6`. The name of your enviornment is `myenv` and we are using the latest complete version of python, 3.9.6. Follow the on screen prompts
   6. Install packages
      1. Run `pip install `
      2. Run `pip install `

# Exploratory Data Analysis

# Data Preprocessing

# Model Development
