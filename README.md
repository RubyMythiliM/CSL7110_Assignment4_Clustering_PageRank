# CSL7110 - Machine Learning with Big Data
## Assignment 4: Clustering and PageRank

**Student:** Ruby Mythili M
**Roll Number:** M25DE1006
**Course:** CSL7110 - ML with Big Data
**Institute:** IIT Jodhpur

---

## 📌 Overview

This assignment covers three major topics:

1. **Part 1 - Clustering:** Farthest First (k-center) and K-Means++ algorithms on the UCI Spam dataset
2. **Part 2 - Web Search:** Building an Inverted Index and TF-IDF based Search Engine
3. **Part 3 - PageRank:** Implementing the PageRank algorithm using Apache Spark

---

## 📁 Repository Structure
CSL7110_Assignment4_Clustering_PageRank/
│

│
├── data/
│   ├── clustering/       # UCI Spam dataset (spambase.data)
│   ├── websearch/        # Webpages, actions.txt, answers.txt
│   └── pagerank/         # whole.txt and small.txt graph files
│
├── notebooks/            # Jupyter notebooks for all 3 parts
│
├── src/                  # Helper Python scripts
│
├── outputs/
│   ├── clustering/       # Clustering results and plots
│   ├── websearch/        # Search engine outputs
│   └── pagerank/         # PageRank scores
│
├── report/               # Final PDF report
│
├── requirements.txt      # Required Python libraries
└── .gitignore
---

## 🛠️ Setup Instructions

1. Clone this repository:
git clone https://github.com/RubyMythiliM/CSL7110_Assignment4_Clustering_PageRank.git
2. Install dependencies:
pip install -r requirements.txt

3. Open notebooks in Google Colab or Jupyter

---

## 📊 Parts Summary

### Part 1: Clustering
- Dataset: UCI Spambase (4601 points, 58 dimensions)
- Algorithms: Farthest First Traversal, K-Means++
- Objective: Compare clustering quality using k-means objective function

### Part 2: Web Search
- Built a custom Inverted Index from scratch
- Implemented TF-IDF scoring for search relevance
- Tested against provided actions.txt and answers.txt

### Part 3: PageRank
- Graph: 1000 nodes, 8192 edges
- Algorithm: Iterative PageRank with β = 0.8, 40 iterations
- Implemented using Apache Spark RDDs

---

## 📄 Report

The final report is available in the `report/` folder.

