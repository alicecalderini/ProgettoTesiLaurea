# Valutazione di modelli di traduzione automatica per l'arricchimento dei dati linguistici italiani: un esperimento con il dataset LAION
Enriching Italian Linguistic Data through Machine Translation

## Overview

This repository contains the code, experiments, and analysis developed for my **Bachelor’s Thesis**.

The project investigates whether **automatic translation can be used to enrich Italian linguistic resources** by translating multimodal data from English to Italian.

The study compares the performance of three machine translation models on a subset of the **LAION dataset**, evaluating their ability to produce reliable translations suitable for dataset augmentation.

---

# Research Objective

Italian language resources are often **less abundant than English datasets**, which can limit the performance of machine learning and translation models.

The goal of this research is to evaluate whether **automatic translation can be used to expand Italian-language datasets**, maintaining adequate translation quality.

---

# Dataset

The experiments are conducted on a **subset of the LAION dataset**, which contains multimodal data linking images with textual descriptions.

The dataset was divided into two parts:

### Gold Dataset

A subset manually translated into Italian and used as a **reference benchmark** for evaluating translation quality.

### Unsupervised Dataset

A larger portion automatically translated by the evaluated models and analyzed without human reference translations.

---

# Models Evaluated

The study compares three machine translation models:

* **Madlad**
* **Helsinki**
* **Phi**

Each model was used to translate English captions into Italian.

---

# Methodology

The evaluation combines **quantitative and qualitative analysis**.

### Quantitative Evaluation

Performance was measured by comparing model outputs with the gold translations using standard evaluation metrics.

### Qualitative Evaluation

Translations were manually inspected to analyze:

* translation accuracy
* semantic consistency
* handling of ambiguities
* preservation of original meaning

---

# Results

The analysis highlights differences between models in terms of:

* fidelity to the original text
* translation coherence
* robustness when translating multimodal captions

The results provide insights into **the potential and limitations of machine translation for enriching Italian-language datasets**.

---

⚠️ **Note:**
File paths and folder organization may change as the repository structure evolves.

---

# Author

Alice Calderini
Bachelor’s Thesis Project

