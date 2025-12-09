# Social Network Analysis & Interactive Visualization

This project explores social network structures using real-world and synthetic datasets.  
It demonstrates data preprocessing, graph construction, network visualization, and interactive graph exploration using Python and JavaScript.

The project was originally completed as part of a data visualization course, but it has been reorganized and documented as a standalone portfolio project.

---

## Project Overview

The analysis focuses on two datasets:

### **1. Monkey Interaction Network**
A weighted adjacency matrix describing interaction frequency between monkeys.  
Steps included:
- Importing and reordering the adjacency matrix using pandas
- Converting the matrix into an edgelist
- Creating a graph using NetworkX with node attributes (age, sex)
- Encoding:
  - **Node color:** Gender  
  - **Node size:** Age  
  - **Edge width:** Interaction weight  
- Visualizing the network using Matplotlib
- Exporting an interactive network visualization using **PyVis** and **vis-network.js**

### **2. Personal Social Network**
A smaller adjacency matrix describing relationships between individuals in a friend group.  
Steps included:
- Converting the adjacency matrix to an edgelist
- Building an unweighted NetworkX graph
- Adding labeled edges
- Visualizing the structure and strongest relationships

---

## Tools & Libraries

**Python**
- pandas  
- numpy  
- matplotlib  
- networkx  
- pyvis  

**JavaScript (for interactive output)**
- vis-network.js  
- utils.js (custom interaction functions)
