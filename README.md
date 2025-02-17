# 🦆 Sea Duck Genomic Analysis & Phylogenetic Tree Construction

## 📌 Project Overview
This project explores the evolutionary relationships between different North American sea duck species using genomic data. It follows a comprehensive bioinformatics workflow:

1. **Data Exploration and Cleaning**
2. **GenBank Sequence Retrieval**
3. **Sequence Alignment**
4. **Phylogenetic Tree Construction**
5. **Visualization**

The goal is to provide insights into sea duck evolutionary history and diversity by analyzing their genomic sequences and visualizing phylogenetic relationships.

---

## 📊 Features

- **Data Loading & Exploration:**
  - Import sea duck genomic data from a CSV file.
  - Perform initial data exploration (e.g., check missing values, duplicates).
  - Visualize species distribution using count plots.

- **GenBank Sequence Retrieval & Alignment:**
  - Fetch DNA sequences from GenBank using Biopython's Entrez module.
  - Perform multiple sequence alignment (MSA) using Clustal Omega.

- **Phylogenetic Tree Construction & Visualization:**
  - Construct a phylogenetic tree from aligned sequences.
  - Visualize the tree using Biopython, matplotlib, plotly, and networkx.
