# Spy-Networks-Covert-Communication-Patterns-in-Social-Media

# Project Description
Espionage and covert intelligence operations have historically relied on hidden communication structures, trusted intermediaries and compartmentalised relationships to reduce exposure. Many networks often have broker nodes that occupy structurally important positions by connecting weakly linked or separated groups. They can be identified using network measures that capture control over shortest paths and inter-group connectivity.

Handlers or intermediaries, are also brokers, mainly found in many spy networks, where they coordinate communication between compartments while limiting direct contact between groups. Such roles cannot be observed directly, but can be inferred when broker nodes exhibit high betweenness, lie between distinct communities and maintain relatively limited direct connectivity.

This project investigates how network analysis techniques can be used to detect suspicious communication structures resembling spy rings. You will construct and analyse an email communication graph derived from the Enron email corpus, a well-known real-world dataset of organizational communications. You will be applying centrality measures, community detection and comparisons against random graph baselines to uncover how covert coordination might manifest in network form. The project will involve exploring key concepts including weak ties, brokerage, small-world structure and anomaly detection in social graphs. Such methods have high relevance in cybersecurity, counter-terrorism intelligence, fraud investigation and organisational risk monitoring.

# Network dataset

This project uses the Enron Email Network dataset provided by the Stanford Large Network Dataset Collection (SNAP) [2]. The dataset contains email communication records between Enron employees. Nodes represent unique email accounts, and directed edges represent email exchanges between accounts. The network contains thousands of nodes, so try to extract a manageable to ensure at least 200 nodes while keeping analysis feasible on a standard laptop.

# Dataset link: https://snap.stanford.edu/data/email-Enron.html

# Tasks
This project contains 4 major tasks and are shown below:

Task 1: Network Construction and Structural Characterisation
Task 2: Broker and Intermediary Detection
Task 3: Random Network Baseline Comparison
Task 4: Covert Cluster and Anomaly Detection
