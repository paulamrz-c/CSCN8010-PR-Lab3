# CSCN8010 - Practical Lab 3 

Welcome to my repository for **Lab Lab 3 Vanilla CNN and Fine-Tune VGG16 - for Dogs and Cats Classification**.

## This repository contains:

### 📓 - The Jupyter Notebook

The notebook `CCSN8010_lab3_VanillaCNN.ipynb` builds and compares two predictive models for binary image classification using a reduced version of the Cats vs Dogs dataset. The goal is to evaluate the performance of a custom CNN versus a fine-tuned VGG16 model to determine which is more suitable for accurately classifying pet images. Throughout the notebook, model evaluation includes accuracy, precision, recall, F1-score, and analysis of misclassified examples.


### HTML Export (for GitHub Pages)
You can view the published notebook [here](https://paulamrz-c.github.io/CSCN8010-PR-Lab3/CSN8010_lab3_VanillaCNN.html)

### 📁 Dataset

The dataset used in this lab is a reduced version of the **Cats vs Dogs** dataset originally from Kaggle.  
Only 5,000 images were used (2,000 for training, 1,000 for validation, and 2,000 for testing), evenly split between cats and dogs.  
The dataset was preprocessed by resizing the images to 100×100 or 150×150 pixels and organizing them into separate folders for training, validation, and test sets.



## 🚀 Quick Start

```bash
python -m venv venvPR
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
.\venvPR\Scripts\activate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv --display-name "Python PR (venv)"
jupyter notebook

```
**Paula Ramirez**
