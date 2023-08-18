# A Computational Approach to CRISPR Reagent Design

This repository contains code and resources for "A Computational Approach to CRISPR Reagent Design" module of the Developmental Genetics undergraduate lab course at Johns Hopkins University. It has been updated here to serve as a standalone resources for anyone interested in creating CRISPR reagents via Python.

These notebooks were developed jointly by [Dylan Taylor](https://dtaylo95.github.io/) and [Sara Carioscia](https://scarioscia.github.io/) as part of their Instructional Enhancement Grant from the [Johns Hopkins Center for Teaching Excellence and Innovation](https://ctei.jhu.edu/programs-and-services/instructional-enhancement-grant-program).

## Module Purpose

This module is designed to 
1) Introduce biology students with little prior coding experience to the basics of computer programming  
2) Create a workspace for students to apply these fundamental Python skills 
3) Build a program to generate reagents for *any* CRISPR-Cas9 experiments

The module comprises several iPython notebooks. Each notebook acts as a skeleton that students can then use to write their own code. These notebooks are made available  to students through Jupyter Notebook and launched via [Google Colab](https://drive.google.com/drive/folders/1MUERIV1NhmkFKbnEgbE7ZV5-zk78uVJc?usp=sharing), allowing them to work together and enabling instructors to provide feedback directly in the notebook.

## Module Schedule 

* Weeks 1 and 2: Students learn the basics of Python programming and Jupyter Notebooks (accessed via Google Colab). These notebooks are in the [intro_notebooks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/intro_notebooks) directory. Students then complete two homework assignments in the [homeworks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/homeworks) directory to reinforce these Python skills, which are integral for the CRISPR reagent design.

* Week 3: Students apply these skills to identify (for a given modification of a given gene) 1) the PAM sequence closest to the site of modification and 2) the crRNA sequence corresponding to this PAM (CRISPR Homework 1 in the [homeworks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/homeworks) directory).

* Weeks 4 and 5: Students develop the repair template corresponding to this same modification (CRISPR Homework 2 in the [homeworks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/homeworks) directory).

## Using the Module 

### Jupyter Notebooks 

To use the resources as Jupyter Notebooks, `git clone` the repository on your local machine and then launch each notebook from the command line via `jupyter notebook notebookname`. Your changes to the notebook will be automatically saved, so feel free to add additional code or markdown cells as are helpful for you. 

### Google Colab

To launch these resources in Google Colab (see notebook [here](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/blob/crispr-nbs/intro_notebooks/How_to_Use_Google_Colab.ipynb) for an overview), `git clone` this repository on your local machine. Then, open a new Google Colab document (similar to how you would open a Google Doc or Google Sheet); File --> open notebook --> upload, and choose your notebook. These changes will **not** be saved, unless you download the notebook back out of Google Colab and place it in your local repository.

## Updating the Module  

Feel free to use this if you have a group of students who might benefit - or if you're a curious biologist yourself! Reach out directly to Dylan (dtaylo95@jhu.edu) or Sara (saracarioscia@jhu.edu) if you have any questions or suggestions. If there's a feature or other update you'd like added, please submit an issue directly on GitHub. 