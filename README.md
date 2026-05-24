# Iris Flower Classification Optimization using PSO & GWO

## Overview
This project applies two meta-heuristic optimization algorithms:
- Particle Swarm Optimization (PSO)
- Grey Wolf Optimizer (GWO)

to optimize the hyperparameters of a Random Forest classifier for Iris flower classification.

The project was developed as part of the Optimization Techniques course.

---

## Objective
The main goal was to improve classification accuracy by automatically tuning Random Forest hyperparameters instead of using manual parameter selection.

---

## Technologies Used
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Optimization Algorithms
### Particle Swarm Optimization (PSO)
- Population-based optimization
- Inspired by bird flocking behavior
- Achieved the highest accuracy

### Grey Wolf Optimizer (GWO)
- Inspired by grey wolf hunting behavior
- Uses alpha-beta-delta hierarchy

---

## Dataset
- Iris Flower Dataset
- 3 Classes:
  - Setosa
  - Versicolor
  - Virginica
- Data Augmentation using Gaussian Noise

---

## Results

| Model | Accuracy |
|------|------|
| Baseline Random Forest | 90.00% |
| PSO Optimized | 96.67% |
| GWO Optimized | 93.33% |

---

## Key Features
- Hyperparameter Optimization
- Comparative Analysis
- Confusion Matrix Evaluation
- Interactive Dashboard
- Visualization of Results

---

## Project Structure

```bash
Iris-Optimization-Project/
│
├── notebook/
├── report/
├── presentation/
├── images/
└── README.md
