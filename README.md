# Connectome Analysis II 

## Introduction

The continuation of Connectome Analysis project involves exploring the structural connectivity of the brain using network analysis techniques. This project focuses on analyzing the connectome of the Macaque Rhesus brain, as it was more feasible within the project timeframe than a Human connectome. The analysis aims to understand the properties of neural networks, identify critical nodes, and explore the implications for diseases like Alzheimer's and Schizophrenia.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data](#data)
- [Analysis](#analysis)
- [Results](#results)
- [Discussion](#discussion)
- [References](#references)

## Project Structure

    data/: Contains the dataset files.
    scripts/: Python scripts for data processing and analysis.
    requirements.txt: Lists the Python dependencies for the project.
    README.md: This README file.

## Data

The dataset includes neural connectivity data from the Macaque Rhesus brain. The data was collected using diffusion-weighted magnetic resonance imaging (DWI or DW-MRI), which maps the diffusion of water molecules in biological tissues to reveal microscopic details about tissue architecture and synaptic connections between neurons.
Analysis

The analysis is divided into several key objectives:

### Explore Nodal and Network Properties:
- Average Degree: Measures the average number of physical connections.
- Betweenness: Indicates how many shortest paths pass through a neuron.
- Participation Coefficient: Measures the diversity of a node's connections to different network modules.
- Identify Hubs and Bridges: Key nodes critical for overall connectivity.
- Network Density and Louvain Communities: Measure overall connectivity and identify community structures.
- Rich Club Subgraph Visualization: Visualize highly connected nodes.

  ### PageRank and Hubness:
  - Compare PageRank results with centrality measures to identify important neurons.

  ### Neuroplasticity and Network Infection:
  - Simulate the propagation of action potentials using an epidemic model to explore how synaptic plasticity affects network connectivity.

  ### Critical Neurons for Disease Prevention:
  - Identify neurons crucial for maintaining small-world properties and explore their roles in preventing Alzheimer's and Schizophrenia.

## Results

### Nodal and Network Properties

The network analysis revealed several key properties:

- Average Degree: Nodes have an average of 13 connections.
- Betweenness Centrality: The diameter of the network is 4 with an average path length of 2.71, indicating a small-world network.
- Clustering Coefficient: High clustering coefficient suggests local density of connections.

### PageRank and Hubness

- PageRank analysis was compared with centrality measures to identify key neurons. The results provide insights into the role of neurons in network connectivity.

### Neuroplasticity and Network Infection

- Simulations using epidemic models showed how synaptic plasticity affects the spread of action potentials through the network. This analysis helps understand the dynamics of neuroplasticity.
Critical Neurons for Disease Prevention

- The lesioning experiments indicated that certain nodes are integral to maintaining small-world properties. Understanding these nodes helps in studying diseases like Alzheimer's and Schizophrenia.
Discussion

The analysis provides a comprehensive understanding of the connectome's structure and functionality. Key findings include the identification of important neurons and their roles in network connectivity. The insights gained from this project can be applied to further research in neuroscience and disease prevention.

## References

    Rossi, R. A., & Ahmed, N. K. (2015). The Network Data Repository with Interactive Graph Analytics and Visualization. AAAI.
    Network Repository: Network Data Repository.

For more detailed information, please refer to the full documentation and analysis scripts included in the project repository.
