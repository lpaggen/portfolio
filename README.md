This repository contains submodules, which are projects I wanted to share with future employers. Feel free to explore each of the repositories.

# ACIBILIZER
This repository contains work that I conducted for Cisco as an open-source contributor. You will find different parsers I wrote to extract information and data from the Cisco ACI source code, which I believe contains about 17000 classes. I used regex very extensively for this project. The main part of the project can be found in "jsontoyml.py", which is a lengthy recursive algorithm designed to traverse JSON data structures, and convert JSON configs to .yml Ansible playbooks. Feel free to reach out to me for clarifications on the subject. 

# Data Analysis Projects
The Data Analaysis Projects repository contains Jupyter notebooks of some of my thorough data analysis work on various datasets. In this repository, you will find notebooks on exploratory data analysis, predictive modelling, and classification. These notebooks are entirely written in Python, using Seaborn, Matplotlib, Pandas, Numpy amongst other libraries. A lot of visualization has been done throughout these notebooks, as I aimed to be as clear as possible with my work.

# Natural Language Processing Projects
This repository contains Jupyter notebooks of some NLP tasks I conducted. You will find some simple rule-based hate speech classifiers I worked on, and also some fine-tuning of a BERT model I used to learn about word embeddings in the context of transformer architecture. 

# Python Game Engine
This is a personal project I unfortunately stopped working on when I started my Masters studies at the Department of Advanced Computing Sciences at Maastricht University. This project was essentially a simple, two-dimensional game engine I developed using Pygame. The project uses only Python, and supports basic collisions, line of sight (through a custom raycaster engine I developed), as well as a map editor, in which you can place different obstacles on the map, and load it to experiment with.

# Mathematical Optimization Library
This project is an ongoing work I am doing in parrallel to my studies. I am very interested in Mathematical Optimization, and have therefore decided to develop my own optimizarion library in Java. Currently the project supports basic symbolic derivatives, including chain rule support. I have yet to write a parser to actually make something useful with the code, but it does work, as you can try for yourself. 

In the future, I aim to add a couple of popular algorithms to this project, such as a better implementation of the Linear Program Solver I wrote earlier this year, this time with multithreading support, so I can find solutions to problems even quicker by leveraging the power of the dual simplex method in parrallel with the primal form of the problem. Additionally, I aim to implement support for Golden Search algorithms, Quadratic Interpolation, Line Search, Newton. Quasi-Newton, Gradient-Descent, Interior-Point algorithms, and maybe some elements of Quadratic Programming. 

# Linear Program Solver
As mentioned above, this repository contains Java code for a linear program solver. Currently, it does not return a solution, rather it returns a "final tableau" which you can read the solution off of. This solver actually supports the so-called "2-phase" simplex method, enabling it to solve more complex problems. It will most likely be implemented in my Java Mathematical Optimization at a future stage, once I fix some errors it still has. 

# Genetic Algorithms
This project includes my own implementation of Genetic Algorithms to solve TSP and Knapsack problems. They function about as expected, and are provided in a Jupyter Notebook format. Additionally, I have included an academic report of my work in form of a PDF. 
