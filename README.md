# SVM Kernels Tutorial – How Kernel Choice Shapes Decision Boundaries

This repository contains my mini project for the **Neural Networks and Machine Learning** module at the University of Hertfordshire.

The aim of the project is to **teach** how Support Vector Machines (SVMs) behave when we change:

- the **kernel** (linear, RBF, polynomial), and  
- the **hyperparameters** **C** and **gamma**.

I use a 2D **moons dataset** from scikit-learn and visualise how the decision boundary changes in each case.

Repo URL:  
https://github.com/RohithRamesh24/svm

---

## Contents

- `svm_kernels_tutorial.ipynb`  
  Jupyter notebook with:
  - generation of the moons dataset  
  - training SVMs with different kernels (linear, RBF, polynomial)  
  - experiments with different values of **C** and **gamma**  
  - visualisations of decision boundaries  
  - a simple `GridSearchCV` example for tuning C and gamma

- `transcript.txt`  
  The full transcript of the video tutorial explaining the project in simple English.

- `LICENSE`  
  MIT License for this repository.

## How to Run the Notebook

1. Clone the repository:

   ```bash
   git clone https://github.com/RohithRamesh24/svm.git
   cd svm
   pip install numpy matplotlib scikit-learn jupyter

