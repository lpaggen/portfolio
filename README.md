This repository contains submodules, which are projects I wanted to share with future employers. Feel free to explore each of the repositories.

# ACIBILIZER
This repository contains work that I conducted for Cisco as an open-source contributor. You will find different parsers I wrote to extract information and data from the Cisco ACI source code, which I believe contains about 17000 classes. I used regex very extensively for this project. The main part of the project can be found in "jsontoyml.py", which is a lengthy recursive algorithm designed to traverse JSON data structures, and convert JSON configs to .yml Ansible playbooks. Feel free to reach out to me for clarifications on the subject. 

# Deep Learning Forecasts
This repository contains some code I wrote to fit a LSTM neural network to a weather forecasting problem. Note that I was interested in forecasting weather in this case, not predicting it. Additionally, as a benchmark to compare the LSTM's forecasts, I have fitted a SARIMA model to the data I had, which turns out to perform better. All prior stationarity tests were conducted correctly on the data before any model was fit on it, and over 200 thousand data points of data was analyzed. 

# Data Analysis Projects
The Data Analaysis Projects repository contains Jupyter notebooks of some of my thorough data analysis work on various datasets. In this repository, you will find notebooks on exploratory data analysis, predictive modelling, and classification. These notebooks are entirely written in Python, using Seaborn, Matplotlib, Pandas, Numpy amongst other libraries. A lot of visualization has been done throughout these notebooks, as I aimed to be as clear as possible with my work.

# Natural Language Processing Projects
This repository contains Jupyter notebooks of some NLP tasks I conducted. You will find some simple rule-based hate speech classifiers I worked on, and also some fine-tuning of a BERT model I used to learn about word embeddings in the context of transformer architecture. 

# Python Game Engine
This is a personal project I unfortunately stopped working on when I started my Masters studies at the Department of Advanced Computing Sciences at Maastricht University. This project was essentially a simple, two-dimensional game engine I developed using Pygame. The project uses only Python, and supports basic collisions, line of sight (through a custom raycaster engine I developed), as well as a map editor, in which you can place different obstacles on the map, and load it to experiment with.

# Custom Programming Language (MrSCL DSL)
This is an interpreted language I'm building using Java. It currently has support for linear algebra types, such as matrices, can compute determinants, and a bit more. The language also supports the usual while loops, if-elseif-else blocks, function calls, and I'm adding support for graph data types, which are mathematical graphs. Currently, you can build graphs, directed, undirected, weighted, unweighted. Check it out, it's a cool project. It currently stands at around 5000 lines of Java code. 

# Linear Program Solver
As mentioned above, this repository contains Java code for a linear program solver. Currently, it does not return a solution, rather it returns a "final tableau" which you can read the solution off of. This solver actually supports the so-called "2-phase" simplex method, enabling it to solve more complex problems. It will most likely be implemented in my Java Mathematical Optimization at a future stage, once I fix some errors it still has. 

# Genetic Algorithms
This project includes my own implementation of Genetic Algorithms to solve TSP and Knapsack problems. They function about as expected, and are provided in a Jupyter Notebook format. Additionally, I have included an academic report of my work in form of a PDF. 
