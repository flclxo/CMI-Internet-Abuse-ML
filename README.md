# CSCI395-Project
Child Mind Institute — Problematic Internet Use

https://www.kaggle.com/competitions/child-mind-institute-problematic-internet-use

We ranked top 25% at 889th place! https://www.kaggle.com/bartswift/competitions

This is a data science project by Kelvin Yu, Daniel Kaijzer, Devin Xie, Bergen and Gabriel Delgado.

Final Presentations: Friday, December 13 and December 20 (1:45-3:45): 
Monday, December 23: Final Reports due

Task 1: Project Design \
Task 2: Comprehensive EDA and Baseline Modeling \
Task 3: Model Improvement and Evaluation \
Task 4: Integrate Features and Testing on Test Set \
Task 5: Final Report

## Set up
#### Create a python virtual environment
1. Make sure you are in the repository's directory. Then, in your command line, run ```python3.10 -m venv .my_env```    
**Note:** ``.my_env`` can be replaced with any preferred name (Make sure to add your virtual environment folder to the .gitignore file)

2. In your command line, run ``pip install -r requirements.txt``
#### Downloading the kaggle dataset
1. In your command line, run ```kaggle competitions download -c child-mind-institute-problematic-internet-use``` 
2. There should be a zip file that will be downloaded to your local repository.   
Now in the command line, run ```unzip child-mind-institute-problematic-internet-use.zip```   
This will download the entire kaggle dataset   
Create a folder and name it ```child_mind_dataset```, then move all the downloaded files and folders into it.   
This folder is already added to the .gitignore file to prevent large files like this from being pushed onto the remote repository.
