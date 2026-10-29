# Graphs and Networks Course Project

A final project completed as part of the **Graphs and Networks** course during graduate studies (M.Sc. in Neuroscience, Tel Aviv University). This project explores structural, topological, and community properties of complex networks, implementing network analysis algorithms and empirical graph evaluations.

---

## Collaborators
* **Gaia Negev**
* **Joseph Schwartz**
* **Ilya Ernston**

---

## Project Overview

The objective of this project was to analyze graph structures and complex network topologies using empirical datasets and computational models. 

### Key Objectives & Deliverables
* **Structural & Topological Analysis:** Characterizing global and local network properties (degree distributions, clustering coefficients, path lengths, centrality measures).
* **Community Detection & Modularity:** Identifying functional subnetworks, partitions, and modular organization.
* **Network Models & Comparison:** Evaluating observed network metrics against theoretical benchmark models (e.g., Erdős–Rényi random graphs, Watts–Strogatz small-world, or Barabási–Albert scale-free networks).
* **Reporting:** Synthesizing the experimental setup, algorithmic behavior, visualizations, and empirical findings into a comprehensive final submission report.

---

## Tools & Technologies

* **Programming Language:** Python
* **Network Analysis:** `NetworkX` (graph construction, routing, centrality metrics, and community detection)
* **Data Manipulation & Computation:** `NumPy`, `pandas`, `SciPy`
* **Data Visualization:** `matplotlib`, `seaborn` (degree distribution fits, adjacency matrices, community network layouts)

---

## Methods

1. **Graph Preprocessing & Construction**
   * Parsing edge lists / adjacency matrices into directed or undirected, weighted or unweighted graph objects.
   * Isolating the giant connected component (GCC) where appropriate and filtering isolated nodes/self-loops.

2. **Topological Metrics**
   * **Degree & Strength Distributions:** Estimating heavy-tailed vs. Poisson-like behavior.
   * **Centrality Profiling:** Degree centrality, Betweenness centrality, Closeness centrality, and Eigenvector/PageRank centrality to detect hub nodes.
   * **Small-Worldness:** Measuring characteristic path length ($L$) and average clustering coefficient ($C$) normalized against randomized null models.

3. **Community & Modularity Analysis**
   * Partitioning graphs using modularity optimization algorithms (e.g., Louvain / Greedy Modularity).
   * Visualizing community partitions and calculating modularity scores ($Q$).
