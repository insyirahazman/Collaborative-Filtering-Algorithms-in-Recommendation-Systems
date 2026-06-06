# Collaborative Filtering Algorithms in Recommendation Systems

This repository contains the implementation, theoretical analysis, and experimental evaluation of Collaborative Filtering (CF) algorithms for recommendation systems as part of the **TDA6323 - Algorithm Design and Analysis** course project.

## Project Information

**Course:** TDA6323 Algorithm Design and Analysis

**Group:** Group 2 (Section 1C)

**Project Title:** Collaborative Filtering Algorithms in Recommendation Systems

### Team Members

**Leader**

* Nur Insyirah Iman Binti Mohd Azman

**Members**

* Anis Syifaa' Binti Mohd Zaffarin
* Sofia Batrisyia Binti Mohamad Faris
* Kueh Pang Teng

---

## Project Overview

Recommendation systems are widely used in modern applications such as Netflix, Amazon, YouTube, Spotify, and e-commerce platforms to provide personalized suggestions to users. Collaborative Filtering (CF) is one of the most popular recommendation techniques, leveraging historical user-item interactions to predict user preferences.

This project investigates and compares several Collaborative Filtering algorithms in terms of:

* Algorithm design
* Time complexity
* Scalability
* Recommendation accuracy
* Experimental execution time

---

## Algorithms Studied

### 1. User-Based Collaborative Filtering (UBCF)

* Memory-based recommendation approach
* Identifies users with similar preferences
* Generates recommendations based on neighboring users

### 2. Item-Based Collaborative Filtering (IBCF)

* Memory-based recommendation approach
* Identifies similar items based on user ratings
* Commonly used in large-scale recommendation systems

### 3. KNN-Based Collaborative Filtering

* Extension of traditional collaborative filtering
* Utilizes K-Nearest Neighbors (KNN)
* Improves recommendation efficiency and accuracy

### 4. Matrix Factorization (SVD)

* Model-based collaborative filtering technique
* Decomposes the user-item matrix into latent factors
* Popularized through the Netflix Prize competition

---

## Dataset

The experiments are conducted using the **MovieLens 100K Dataset**.

Dataset Source:
https://grouplens.org/datasets/movielens/100k/

The dataset contains:

* 100,000 ratings
* 943 users
* 1,682 movies

---

## Experimental Setup

All algorithms are implemented in **Python** and evaluated using different dataset sizes:

| Dataset Size    |
| --------------- |
| 10,000 Ratings  |
| 20,000 Ratings  |
| 40,000 Ratings  |
| 60,000 Ratings  |
| 80,000 Ratings  |
| 100,000 Ratings |

### Evaluation Metrics

* Execution Time (ms)
* Root Mean Square Error (RMSE)
* Mean Absolute Error (MAE)

---

## Project Structure

```text
.
├── User-Based-CF/
├── Item-Based-CF/
├── KNN-Based-CF/
├── Matrix-Factorization/
├── datasets/
├── results/
├── graphs/
├── report/
└── README.md
```

## Research Objectives

1. Study the evolution of Collaborative Filtering algorithms.
2. Compare memory-based and model-based recommendation techniques.
3. Analyze the theoretical time complexity of each algorithm.
4. Evaluate algorithm performance through experimental analysis.
5. Propose an improved recommendation framework.

---

## Proposed Improvement

The project proposes a:

**Community-Aware Adaptive KNN Matrix Factorization**

which combines:

* Community Detection
* Adaptive K-Nearest Neighbors
* Matrix Factorization

to address:

* Data Sparsity
* Cold-Start Problem
* Scalability Issues
* Recommendation Diversity

---

## References

All datasets, papers, and external code sources used in this project are properly cited in the final report.

---

## Disclaimer

This repository is developed solely for academic purposes under the TDA6323 Algorithm Design and Analysis course at Multimedia University (MMU).
