# Wikipedia Text Classification 

## Content

- [Overview](#overview)
- [Dataset Description](#the-dataset-description)
- [Install](#install)
- [Project Structure](#project-structure)

---

## Overview

## The Dataset Description

- 
- 
- 
- 
- 
- 

## Install

```
clone git@github.com:Melak2017/NLP-Text-Classification.git
pip install -r requirements.txt
```

---

## Project Structure

    .
    ├── .github/workflows              # github actions
    ├── data                           # data directory
        ├── labeled.csv             # labeld medical/non-medical data           
        ├── topic.json              # dictionary for clasifiying topic texts                   
    ├── logs                           # log files
    ├── model                         # dumped model                        
│   │   ├── text_classifier_model.py     
    │
    ├── notebooks                      # Jupyter notebooks for exploration and experimentation 
    │   ├── pre_processing.ipynb      # notebook containing processing and modeling
    │
    ├── src                        # # Scripts modules for data pre-processing 
    |    ├── data_cleaner.py           # a python script for cleaning pandas dataframes.
    |
    ├── tests                          # directory for unit testing
    |    
    ├── requirements.txt               # a text file lsiting the projet's dependancies
    ├── .gitignore                     # files to ignore when committing
    ├── setup.py                       # a configuration file for installing the scripts as a package
    ├──LICENSE                         # license file
    └── README.md                      # Markdown text with explanation of the project and the structure.

---

[back to top](#content)
