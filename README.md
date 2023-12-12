# Homework_4_MA
This is the homework 4 of the course Marketing Analytics. In this homework I do Social Network Analysis. Data of connections is provided. 
The tasks of the homework include finding the most important nodes find bridges, communities and in the end build a business model.
Necessary libraries and packages to import and load:

import networkx as nx
from networkx.algorithms.community import greedy_modularity_communities
import matplotlib.pyplot as plt
from operator import itemgetter
