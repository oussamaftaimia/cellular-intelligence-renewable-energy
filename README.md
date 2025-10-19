Cellular Intelligence for Renewable Energy Networks

This repository implements a Physarum-inspired approach to optimize energy infrastructure layout by mimicking the behavior of Physarum polycephalum, a slime mold known for forming efficient transport networks. The system learns from real urban and energy data to simulate network growth and optimization.

-Project Highlights

Bio-Inspired Optimization: Based on the slime mold's ability to connect nutrient sources using minimal cost paths.

Training Phase: Tokyo railway system is used as a reference (replicating Physarum’s successful reproduction of Tokyo’s network).

Testing Phase: Applied to Namibia's solar potential and settlements to evaluate renewable energy layout planning.

Scalable Framework: Designed to extend to any geographic location with elevation, demand, and energy resource data.

-Datasets
1. tokyo-station20180330_Dataset.csv

Contains coordinates and metadata for Tokyo metro stations.

Used as nodes in training the graph structure.

2. tokyo_rail_edges.csv

Represents edges and distances between Tokyo stations.

Basis for graph topology that mimics Physarum’s pathfinding.

3. namibia_dre_atlas_settlements.csv

Settlement locations, population, demand, PV potential, and proximity to infrastructure.

Used to test the Physarum-inspired energy distribution model.


-Potential Machine Learning Models 

Linear Regression: Estimate energy demand or capacity needs.

K-Means Clustering: Group demand centers or source locations.

Decision Trees / Random Forests: Classify optimal vs suboptimal routes.

Support Vector Machines (SVM): For terrain-aware or resource classification.

Reinforcement Learning (RL): Learn dynamic energy routing policies.

Graph Neural Networks (GNNs): Predict edge activations or simulate network evolution.

Deep Q-Learning: Advanced RL for policy optimization across regions.

These models can be integrated at different stages to enhance prediction, routing, or system robustness.
