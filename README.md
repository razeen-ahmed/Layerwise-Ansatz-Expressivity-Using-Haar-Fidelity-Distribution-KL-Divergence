# Layerwise Ansatz Expressivity Using Haar Fidelity Distribution & KL Divergence

This repository contains a research notebook that explores the expressivity of quantum neural network ansatzes using **Haar fidelity distribution** and **Kullback-Leibler (KL) divergence** as quantitative measures. The analysis is performed layer-wise to understand how expressivity evolves with network depth.

## 🧪 Objectives

- Evaluate the expressivity of various quantum circuit ansatzes.
- Use Haar fidelity as a statistical benchmark to assess randomness.
- Measure KL divergence between sampled fidelities and the Haar distribution.
- Compare shallow vs deep circuits in terms of expressivity.

## 📓 Notebook Overview

The main notebook:
- Sets up the simulation environment.
- Defines a set of ansatzes with increasing layer depth.
- Simulates random parameterizations.
- Computes fidelity distribution against Haar-random states.
- Plots and analyzes the resulting expressivity landscape.

## 🧰 Technologies Used

- Python (Jupyter/Colab)
- NumPy
- Matplotlib
- SciPy
- Qiskit

## 📊 Key Concepts

- **Ansatz Expressivity**: The ability of a quantum circuit to represent a wide variety of quantum states.
- **Haar Distribution**: The theoretical distribution of fidelities for perfectly random unitary transformations.
- **KL Divergence**: A statistical tool to compare the empirical fidelity distribution against the Haar baseline.

## 🧮 Results

The notebook provides:
- Layerwise plots of expressivity on a graph.
- Quantitative KL divergence values showing how closely each ansatz mimics Haar randomness.
- Insights into optimal circuit depth for expressive and trainable quantum models.

## 📁 How to Use

1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter.
3. Run all cells from top to bottom.
4. Modify ansatz parameters or layer count to explore further.

## 🤝Code Access

Please reach out to me via email for the access of the code.

## 📜 License
MIT License

## Inspired From these papers
-https://arxiv.org/abs/1905.10876 
-https://arxiv.org/pdf/2108.00661

---

*For any questions or collaboration opportunities, please reach out via GitHub or email.*
**email:** ahmedshadman12@gmail.com

