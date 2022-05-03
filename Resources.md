# Practice Squad Training
Very humbled to have you here to check out what we hope will be the start of a great group and forum for innovating, demoing, and creating. 

This is the first iteration, so there may be areas with room for improvement. 

## Table of Contents
0. Download and Install Software
1. Enviornment SetUp
2. EDA
3. Preprocessing
4. Model Development
5. Useful GitHub Repos

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
   * `Azure Machine Learning`
   * `Github Repositories`
   * `rainbow csv`
3. Create your conda environment and install the necessary packages in here **once** so that you can reuse this environment for future work.
   1. Open a new terminal by clicking on "Terminal" at the top and "New Terminal"
   2. Click "Allow" when a pop up appears asking if you allow the workspace to modify your terminal shell.
      * If you see "PS" next to your current directory on the command line, that means you're using powershell and we don't want to use that. The fix: open a new terminal again and you should now be using cmd.
   3. Since you already installed Anaconda, you should see `conda activate base` run automatically and (base) should be next to your current directory.
   4. Create a new conda enviornment
      - Create environment by running `conda create -n myenv python=3.9.6`. The name of your enviornment is `myenv` and we are using the latest complete version of python, 3.9.6. Follow the on screen prompts
      - Create conda enviornment from the .yml file in this repo:
           * `conda env list`
           * `conda env create -f experiment_env.yml`
           * `conda activate experiment_env`
           * `ipython kernel install --user --name experiment_env --display-name "experiment_env"`
   5. Follow the on screen promts to activate your environment. From the command palette you many need to select your newly created conda enviornment from the **python: select Interpretor** 
   6. If you created a new enviornment, now you can install your packages. If you don't know where to start `seaborn`, `Pandas`, `matplotlib` are good EDA libraries.
         1. Run `pip install __`
         2. Run `pip install __`
4. Resources
- [Definitive Guide to Conda Envionrments | Towards Data Science](https://towardsdatascience.com/a-guide-to-conda-environments-bc6180fc533)
- [Create Enviornment through YML File | Medium](https://sachinjose31.medium.com/creating-an-environment-in-anaconda-through-a-yml-file-7e5deeb7676d)
- [Deploy models trained with Azure Machine Learning on your local machines | Microsoft Docs](https://docs.microsoft.com/en-us/azure/machine-learning/how-to-deploy-local)
   

# Exploratory Data Analysis
- [Exploratory Data Analysis | NIST](https://www.itl.nist.gov/div898/handbook/toolaids/pff/eda.pdf?msclkid=d7346bcfc00911ec93f062f08345b6a6)
- [Car Price Prediction EDA Notebooks | Kaggle](https://www.kaggle.com/code/abhishekumeshparikh/car-price-prediction-eda-basics/notebook)
- [EDA for Machine Leraning | analyticsvidhya](https://www.analyticsvidhya.com/blog/2021/04/rapid-fire-eda-process-using-python-for-ml-implementation/)
- [Knowledge from the data and Data Exploration Analysis | Medium](https://medium.com/ml-research-lab/chapter-4-knowledge-from-the-data-and-data-exploration-analysis-99a734792733)
- [Fnd the right Graphic | from Data to Viz](https://www.data-to-viz.com/)

# Data Preprocessing
- [What Is Data Processing: Cycle, Types, Methods, Steps and Examples | simplilearn](https://www.simplilearn.com/what-is-data-processing-article)
- [Data Pre Processing Techniques You Should Know | Towards Data Science](https://towardsdatascience.com/data-pre-processing-techniques-you-should-know-8954662716d6)
- [Preprocessing data with TensorFlow Transform | Tensorflow](https://www.tensorflow.org/tfx/tutorials/transform/simple)

# Model Development
- [Data Science Methodology From Modelling to Evaluation | Medium](https://medium.com/ml-research-lab/part-4-data-science-methodology-from-modelling-to-evaluation-3fb3c0cdf805)

# Useful Github Repos
- [Azure Data Roadshow Hackathon](https://github.com/memasanz/titantic-dataset-azuredataroadshowhack)
   * Tags: Conda Create from YML file, EDA, Preprocessing, Model Deployment to AML, Batch Inference Pipeline
- [Data Science Your Way](https://github.com/jadianes/data-science-your-way)
   * Tags: Dataframes, EDA, Dimensionality reduction, Sentiment Analysis, Regularisation 
- [How to use AzureML | Azure](https://github.com/Azure/MachineLearningNotebooks/tree/master/how-to-use-azureml)
- [Math Resources for Machine Learning](https://github.com/Machine-Learning-Tokyo/Math_resources)
