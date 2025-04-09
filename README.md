# 📘 Benchmarking and Improving Factual Accuracy of LLMs with Search

## 🔍 Overview

This project presents a curated dataset and experimental analysis that evaluates the **factual accuracy** of various Large Language Models (LLMs) enhanced with search functionality. Despite integration with search tools, our findings show that LLMs still exhibit **factual inconsistencies**.

To mitigate this, we propose a novel **fact-verification pipeline** that significantly improves factual accuracy. We offer this method as a baseline and pose it as an **open research challenge** to the community.

## 📂 Contents

- `dataset/` – Contains curated queries and LLM responses.
- `evaluation/` – Scripts and metrics used for factuality evaluation.
- `pipeline/` – Our proposed method for improving factual accuracy.
- `results/` – Comparative analysis of different models and methods.

## 📊 Key Contributions

- **Dataset Creation:** A benchmark dataset of fact-based queries and LLM-generated answers.
- **Empirical Evaluation:** Demonstrated that LLMs with search still produce _hallucinated facts_.
- **Proposed Pipeline:** A verification-based method that improves accuracy.
- **Open Challenge:** The pipeline is proposed as a base for further research.

## 🤝 Call for Collaboration

We welcome contributions from the community. You can help by:

- Extending the dataset with newer or domain-specific queries.
- Enhancing the verification pipeline.
- Proposing new evaluation metrics or integrating more LLMs.
