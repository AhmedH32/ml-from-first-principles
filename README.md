# Machine Learning from First Principles

A modular, framework-free machine learning library built from scratch using pure NumPy and matrix calculus. The objective of this repository is to bridge the gap between high-level algorithmic intuition and low-level matrix execution.

## 🚀 Architectural Pillars
* **Zero Deep Learning Frameworks:** All classical layers, gradient passes, and node trees are implemented using fundamental linear algebra.
* **Purely Vectorized:** Explicit Python loops are eliminated wherever possible in favor of optimized NumPy broadcasting operations.
* **Production-Grade Design:** Emulates clean object-oriented design patterns with separate source engines (`src/`) and testing configurations (`examples/`).

## 📁 Repository Structure
* `src/supervised/` - Regressions, trees, parametric classifiers.
* `src/unsupervised/` - Clustering and dimensionality reduction.
* `src/deep_learning/` - Modular layers, computational autograd graph, transformers.
* `examples/` - Synthesizing data and executing validation loops.

## 🗺️ Implementation Roadmap
- [ ] Phase 1: Linear Math & Gradient Descent Optimizers
- [ ] Phase 2: Logistic Categorization & Evaluation Metrics
- [ ] Phase 3: Distance Metrics, Clustering, & PCA
- [ ] Phase 4: Non-Linear Trees & Boosting Ensembles
- [ ] Phase 5: Support Vector Machines (Kernels)
- [ ] Phase 6: Deep Learning Computational Graph & Transformers