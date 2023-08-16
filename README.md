# A Computational Approach to CRISPR Reagent Design

This repository contains code and resources for the "A Computational Approach to CRISPR Reagent Design" module of the Developmental Genetics undergraduate lab course at Johns Hopkins University. These resources were developed jointly by [Dylan Taylor](https://github.com/dtaylo95) and [Sara Carioscia](https://github.com/scarioscia) as part of their Instructional Enhancement Grant from the [Johns Hopkins Center for Teaching Excellence and Innovation](https://ctei.jhu.edu/programs-and-services/instructional-enhancement-grant-program).

These resources comprise a 5-week module for the undergradute Developmental Genetics course. During this course, students use the CRISPR-Cas9 system to perform genetics experiments in C. elegans. Designing the necesssary reagents to carry out the desired genetic modification is a major part of the course. 

This module is designed to 
1) introduce biology students with little prior coding experience to the basics of computer programming and 
2) apply these skills to reinforce the process of generating reagents for *any* CRISPR-Cas9 experiments, including in their own research. 

To write code that will be successful with a variety of inputs - and thus applicable to various scenarios in their own research - students must thoroughly understand each step in CRISPR reagent design.

The module comprises several iPython notebooks. Each notebook acts as a skeleton that students can then use to write their own code. These notebooks are made available  to students through [Google Colab](https://drive.google.com/drive/folders/1MUERIV1NhmkFKbnEgbE7ZV5-zk78uVJc?usp=sharing), allowing them to work together and enabling instructors to provide feedback directly in the notebook.

The module is designed to take 5 weeks. During the first two weeks, students learn the basics of Google Colab and Python programming; these notebooks are in the [intro_notebooks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/intro_notebooks) directory. Using the skills they learned from the introduction, students then complete two homework assignments ([01_Python_intro_hw1.ipynb](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/blob/main/homeworks/01_Python_intro_hw1.ipynb) and [02_Python_intro_hw2.ipynb](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/blob/main/homeworks/02_Python_intro_hw2.ipynb) in the [homeworks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/homeworks) directory).

During the third week, students apply these skills to identify (for a given modification of a given gene), 1) the PAM sequence closest to the site of modification and 2) the crRNA sequence corresponding to this PAM ([03_CRISPRDesign_HW1.ipynb](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/blob/main/homeworks/03_CRISPRDesign_HW1.ipynb) in the [homeworks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/homeworks) directory).

During the final two weeks, students develop the repair template corresponding to this same modification ([04_CRISPRDesign_HW2.ipynb](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/blob/main/homeworks/04_CRISPRDesign_HW2.ipynb) in the [homeworks](https://github.com/dtaylo95/A-Computational-Approach-to-CRISPR-Reagent-Design/tree/main/homeworks) directory).

Feel free to use this if you have a group of students who might benefit - or if you're a curious biologist yourself! Reach out directly to Dylan (dtaylo95@jhu.edu) or Sara (saracarioscia@jhu.edu) if you have any questions or suggestions. 