Please see to with that the following pre-requisites are satisfied as the code was tested on the below environments:
Any modification to the below mentioned environments, might need apropriate modifications in the code

Before starting the execution, please refer chapter-01 for an eloborate understanding. Note that the Step_by_step execution might not give you clear conceptual understanding.
It'll only help you build the model and test the output. However, the important functions, steps are given a brief explanation. If you do not understand any module, you 
are advised to refer chapter-01 and the corresponding sub-section.


Editor : Jupyter Notebook
Python Version: 3.7 via Anaconda(If u have other Python versions existing set the paths of all the libraries properly)
(While executing this, I uninstalled all other Python versions because I faced path issues. However, you can change the paths and resolve the issues, if faced)
Note: It is not mandatory to uninstall other Python versions, I uninstalled for my ease

Install latest version of Anaconda by following the required instructions for your Operating System(OS)
The below module of installations and testing was done on Windows 10 64-bit OS
After installing Anaconda follow the below steps:

1) Create a seperate environment on Anaconda command prompt by the following commands
	> conda create -n env_name
2) Activate the environment 
	> conda activate env_name
3) Pip Installation (Ignore if already installed)
	> conda install pip
4) Package Installations
	>pip install pandas
	>pip install numpy
	>pip install sklearn
	>pip install matplotlib
	>conda install graphviz
	>conda install python-graphviz (Run both the commands and restart the kernel and open the notebook in the environment)

5) Checking the installations

The below packages need to be checked if installed or not on python:
To do this, Open Anaconda Prompt > python
>>import pandas
>>import numpy
>>import matplotlib
>>import sklearn
>>import graphviz



Note: Always open the jupiter note-book in the environment as the above installations shall be installed only on the environment

To open Jupyter Notebook in environment:
1) Open Anaconda GUI
2) Click on "Application on" drop down menu
3) Select your env_name(the name which you've given while creating your environment)
4) Jupyter notebook shall be opened on a web-browser
