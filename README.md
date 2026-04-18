# 🚀 CSL7110 – Machine Learning with Big Data

## Assignment 4: Clustering • Web Search • PageRank

👩‍💻 **Author:** Ruby Mythili M

🎓 **Roll Number:** M25DE1006

🏫 **Institute:** IIT Jodhpur


---

## ✨ Project Overview

This repository presents the implementation of core large-scale data processing concepts through three independent modules:

* 🔹 **Clustering Algorithms** – Farthest First (k-center) and K-Means++
* 🔹 **Search Engine Design** – Inverted Index with TF-IDF ranking
* 🔹 **Graph Analytics** – PageRank using Apache Spark

The focus of this work is not just implementation, but understanding how these algorithms behave on real-world scale data.

---

## 🧠 Key Highlights

* Implemented clustering algorithms **from scratch** and analyzed their performance
* Built a **mini search engine pipeline** including indexing and ranking
* Designed a **distributed PageRank system** using Spark RDDs
* Worked with **real datasets** (UCI Spam, web documents, graph data)
* Structured outputs and experiments for **clear reproducibility**

---

## 📂 Repository Structure

```bash
CSL7110_Assignment4_Clustering_PageRank/
│
├── data/
│   ├── clustering/        # UCI Spambase dataset
│   ├── websearch/         # Web documents and queries
│   └── pagerank/          # Graph datasets
│
├── notebooks/             # Implementation notebooks
├── src/                   # Utility scripts
│
├── outputs/
│   ├── clustering/        # Results and plots
│   ├── websearch/         # Ranked outputs
│   └── pagerank/          # Node rankings
│
├── report/                # Final report (PDF)
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Getting Started

```bash
# Clone the repository
git clone https://github.com/RubyMythiliM/CSL7110_Assignment4_Clustering_PageRank.git

# Install dependencies
pip install -r requirements.txt
```

Run the notebooks using **Jupyter Notebook** or **Google Colab**.

---

## 📊 Implementation Details

### 🔹 Part 1: Clustering

* Dataset: **UCI Spambase** (4601 samples, 58 features)
* Algorithms:

  * Farthest First Traversal (k-center)
  * K-Means++
* Evaluation: k-means objective function

👉 Focus: Understanding initialization impact and cluster quality

---

### 🔹 Part 2: Web Search Engine

* Built an **Inverted Index** for document retrieval
* Implemented **TF-IDF scoring** for ranking relevance
* Validated results using provided query-answer pairs

👉 Focus: How real search engines rank documents

---

### 🔹 Part 3: PageRank (Apache Spark)

* Graph: **1000 nodes, 8192 edges**
* Damping factor: **β = 0.8**
* Iterations: **40**
* Framework: **Spark RDDs**

👉 Focus: Scalable graph processing and iterative computation

---

## 📈 Results & Outputs

* Clustering performance comparison plots
* Ranked search results for given queries
* Final PageRank scores for graph nodes

All outputs are available in the `outputs/` directory.

---

## 📄 Report

A detailed explanation of methodology, assumptions, and observations is included in:

```
report/
```

---

## 💡 Learning Outcome

This assignment helped in understanding how core data engineering concepts like:

* **Data partitioning**
* **Distributed computation**
* **Search indexing**
* **Iterative graph algorithms**

are applied in real systems.

---

## 🔗 GitHub

👉 [https://github.com/RubyMythiliM/CSL7110_Assignment4_Clustering_PageRank](https://github.com/RubyMythiliM/CSL7110_Assignment4_Clustering_PageRank)

---

## 👩‍🎓 Author

**Ruby Mythili**
M.Tech – Data Engineering
IIT Jodhpur

---

