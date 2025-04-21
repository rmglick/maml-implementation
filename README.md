# MAML Implementation

This project implements **Model-Agnostic Meta-Learning (MAML)**, a meta-learning algorithm that enables models to adapt quickly to new tasks using only a few training examples.

---

## Files

- `maml-implementation.ipynb` — Main notebook documenting the MAML algorithm, implementation details, and experimental results
- `maml_utils.py` — Helper functions (e.g., task sampling, inner loop updates)
- `datasets/` — Synthetic or few-shot learning datasets (e.g., sinusoid regression, Omniglot, miniImageNet)
- `README.md` — Project overview and instructions

---

## Overview

**MAML** is a meta-learning algorithm that learns a good initialization of parameters such that a model can adapt to new tasks with just a few gradient steps.

The implementation covers:
- Sinusoid regression (as a toy 1D regression task)
- Few-shot classification (if included)
- First-order and second-order versions of MAML
- Performance analysis across different numbers of inner-loop steps and meta-updates

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/maml-implementation.git
   cd maml-implementation

References: 
Fin et al. 2017. "Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks"
