---
title: "Information Theory - Huffman Coding, Lempel-Ziv, and Data Compression"
tags: [mathematics, computer-science, information-theory, algorithms]
related: [[[Information Theory - Shannon Entropy and Channel Capacity]], [[Information Theory - Kolmogorov Complexity and Algorithmic Probability]]]
created: 2026-11-26
updated: 2026-11-26
---

# Information Theory - Huffman Coding, Lempel-Ziv, and Data Compression

## Overview
Data Compression algorithms minimize redundant information representations to encode data within theoretical Shannon entropy limits ($H = -\sum p_i \log_2 p_i$).

## Core Mechanics & Foundations
Huffman Prefix-Free Optimal Coding (1952): A greedy bottom-up tree construction assigning shorter binary codewords to frequently occurring symbols and longer codewords to rare symbols. Because no codeword is a prefix of any other (prefix-free), encoded bitstreams can be decoded unambiguously in real-time.

## Modern Applications & Advanced Significance
Dictionary-Based Compression (Lempel-Ziv LZ77 and LZ78): Rather than counting isolated character frequencies, LZ algorithms dynamically build a dictionary of repeated multi-character string substrings during single-pass scanning, replacing occurrences with `(offset, length)` back-references.

## Real-World Impact & Systems
Foundational architecture of modern lossless compression formats: DEFLATE (ZIP, GZIP), PNG images, HTTP web asset compression.

## Key Terminology
- **Huffman Coding**: Entropy encoding algorithm used for lossless data compression utilizing variable-length prefix-free binary codes.
- **Prefix-Free Code**: Code system where no valid code word in the alphabet is a prefix of any other code word, enabling instant decoding.
- **LZ77**: Lossless data compression algorithm that achieves compression by replacing repeated occurrences of data with references to a sliding window.


## References & Further Exploration
[[Information Theory - Shannon Entropy and Channel Capacity]], [[Information Theory - Kolmogorov Complexity and Algorithmic Probability]]
