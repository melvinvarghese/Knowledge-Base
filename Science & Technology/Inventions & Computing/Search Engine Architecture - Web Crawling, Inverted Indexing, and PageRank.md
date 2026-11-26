---
title: "Search Engine Architecture - Web Crawling, Inverted Indexing, and PageRank"
tags: [computing, information-retrieval, algorithms, web]
related: [[[Eigenvalues, Eigenvectors, and Spectral Decomposition]], [[Markov Chains and Random Walks]]]
created: 2026-11-26
updated: 2026-11-26
---

# Search Engine Architecture - Web Crawling, Inverted Indexing, and PageRank

## Overview
Search engine architectures ingest the World Wide Web, index billions of unstructured text documents, and retrieve relevance-ranked search results in milliseconds.

## Core Mechanics & Foundations
Web Crawling & Inverted Indexing: Web crawlers (spiders) traverse hyperlinks using polite breadth-first queues respecting robots.txt. Raw web pages are tokenized, stemmed, and stored in an Inverted Index—a mapping from each vocabulary term to a sorted posting list of documents containing it with frequency weights (TF-IDF).

## Modern Applications & Advanced Significance
The PageRank Algorithm (Page & Brin, 1998): Models the web as a directed graph where hyperlinks represent authoritative citations. PageRank interprets web browsing as a random walk with damping factor $d \approx 0.85$: $PR(u) = \frac{1-d}{N} + d \sum_{v \in B_u} \frac{PR(v)}{L(v)}$. The stationary eigenvector of the hyperlink transition matrix reveals global page authority.

## Real-World Impact & Systems
Web search engines (Google, Bing), enterprise document search (Elasticsearch, Lucene), recommendation systems.

## Key Terminology
- **Inverted Index**: Data structure mapping individual words to lists of documents or web pages in which they occur.
- **PageRank**: Link analysis algorithm measuring the relative importance of hyperlinked web pages based on eigenvector centrality.
- **TF-IDF**: Term Frequency-Inverse Document Frequency; numerical statistic reflecting how important a word is to a document in a collection.


## References & Further Exploration
[[Eigenvalues, Eigenvectors, and Spectral Decomposition]], [[Markov Chains and Random Walks]]
