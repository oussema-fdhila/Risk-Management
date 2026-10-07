# 📊 PMBOK Risk Management – NLP Analysis

<p align="center">

  <img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python&logoColor=white" alt="Python">

  <img src="https://img.shields.io/badge/NLP-Natural%20Language%20Processing-purple?style=for-the-badge" alt="NLP">

  <img src="https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white" alt="Google Colab">

  <img src="https://img.shields.io/badge/PMBOK-6th%20Edition-orange?style=for-the-badge" alt="PMBOK">

  <img src="https://img.shields.io/badge/Status-Completed-success?style=for-the-badge" alt="Status">

</p>

<p align="center">
  <strong>NLP-based extraction of concepts, keywords and semantic relationships from PMBOK 6</strong>
</p>

---

## 🎯 Project Overview

This project applies **Natural Language Processing (NLP)** techniques to the **PMBOK® Guide – Sixth Edition** in order to transform unstructured project management knowledge into structured information.

The objective is to extract meaningful information from a large knowledge base and make it easier to analyze, explore and visualize.

### The analysis focuses on:

- 🔹 Concept extraction
- 🔹 Keyword extraction
- 🔹 Semantic relationships
- 🔹 Subject–Verb–Object (SVO) triplets
- 🔹 Knowledge graph information
- 🔹 Chapter-level analysis

---

## 🖼️ Project Workflow

```mermaid
flowchart LR

    A["📄 PMBOK 6 PDF"]

    B["🔎 Text Extraction"]

    C["🧹 Text Cleaning"]

    D["📚 Chapter Detection"]

    E["🧠 Concept Extraction"]

    F["🔑 Keyword Extraction"]

    G["🔗 Relationship Extraction"]

    H["📊 Structured Data"]

    I["📈 Data Analysis"]

    J["📊 Visualization"]

    K["🕸️ Knowledge Graph"]

    A --> B
    B --> C
    C --> D

    D --> E
    D --> F
    D --> G

    E --> H
    F --> H
    G --> H

    H --> I
    I --> J

    G --> K
