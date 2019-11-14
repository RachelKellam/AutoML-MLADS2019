# MLADS Workshop Guide: Automated Machine Learning
## Contents
1. [Introduction](#Introduction)
1. [Setup](#Setup)
1. [Part 1 - Automated Machine Learning](#AutomatedML)
1. [Part 2 - Hyperdrive](#HyperDrive)
1. [Resources](#Acknowledgements)


## Introduction
This workshop is split into two parts. In the first part you will use automated machine learning in Azure to create, deploy and understand a classification model using the UCI Bank Marketing dataset. In the second part, you will take a previous built model and further tune the hyper parameters.

This process accepts training data and configurations settings, and automatically iterates through combinations of different feature normalization/standardization methods, models, and hyperparameter settings to arrive at the best model.

![Automated ML Flow](Images\AutoML-Flow-Chart.png)

## Setup

Complete the following experiment set-up to prepare for the workshop
1. Go to ml.azure.com and click "Sign in"
1. Using the credentials given to you by a moderator, sign in to the studio.


1. Click the `Start Now` button in the **Notebooks** pane.
![Start Now](./Images/notebook-startnow.png)

1. In the **Azure Ml gallery** pane select the **"..."** at the right of the **samples** folder and select **Clone**.
![Clone Samples](./Images/clone-samples.png)

1. Select a folder as your target directory for the samples and click `clone` at the bottom right of the pop up.
![Target Directory](./Images/target-dir.PNG)
Now your files are ready!

1. Select the `compute` tab and click on `JupyterLab`. **Your compute should already be provisioned for you.**

    
1. In JupyterLabs, click through the following path **<your-alias>/samples/how-to-use-azureml/automated-machine-learning/forecasting-energy-demand** and open the **auto-ml-forecasting-energy-demand.ipynb** file.
![Open Folder](./Images/notebook-path.PNG)  

 
> [!IMPORTANT]
> You can view notebooks in the **Azure ML gallery** pane but you cannot run a notebook from there.  In order to run a notebook, make sure you open the cloned version of the notebook in the **User Files** section.


## AutomatedML
1. Once the VM is available it will be displayed in the top toolbar.  You can now run the notebook either by using **Run all** in the toolbar, or by using **Shift+Enter** in the code cells of the notebook.

1. The Jupyter notebook contains step by-step guidance on configuration, training and exploration of a machine learning model.
### The rest of this section contains **supplemental

## HyperDrive

1. Once the VM is available it will be displayed in the top toolbar.  You can now run the notebook either by using **Run all** in the toolbar, or by using **Shift+Enter** in the code cells of the notebook.

1. The Jupyter notebook contains step by-step guidance on configuration, training and exploration of a machine learning model.

## Resources

1. What is Automated Machine Learning? : https://docs.microsoft.com/en-us/azure/machine-learning/service/concept-automated-ml

1. How to define ML tasks: https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-define-task-type 

1. Auto-train a forecasting model: https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-auto-train-forecast 

1. Azure ML, New at Ignite: https://azure.microsoft.com/en-us/blog/azure-machine-learning-ml-for-all-skill-levels/ 