# 🕵️‍♂️ Fraud Detection with Classical & Quantum Reinforcement Learning

This project implements a pipeline for **fraud detection in financial transactions** using **Reinforcement Learning (RL)** techniques, with extensions to **Quantum RL**.  
It explores various architectures, reward strategies, and agent setups to optimize decision-making in a fraud-detection scenario using a real-world transaction dataset.

---

## 🧠 Objectives

- Preprocess and engineer features from a transactional dataset (banking/fraud)
- Implement and evaluate classical RL agents (e.g., Actor-Critic)
- Automate experiments over different RL parameters and reward schemes
- Explore integration of **Quantum RL** models for advanced detection tasks
- Compare performance (e.g., precision, recall, loss) across setups

---

## 📂 Notebooks

| Notebook | Description |
|----------|-------------|
| `Actor_Policy.ipynb` | Actor-Critic architecture for fraud decision modeling |
| `Experiment_1_Best.ipynb` | A complete end-to-end RL setup with tuned hyperparameters |
| `Automatic_experinment.ipynb` | Batch testing different agent settings and reward strategies |
| `QRL.ipynb` | Experimental extension toward Quantum Reinforcement Learning methods |

---

## 🧪 Features

- Derived features: balance differentials, amount-to-balance ratios, suspicion flags
- Rolling statistics and sequential transaction features
- Reward shaping and strategy experimentation
- Modular agent training with reproducible experiments

---

## 📊 Technologies Used

- Python 3
- NumPy, Pandas, Scikit-learn
- TensorFlow / Keras (for policy models)
- Custom RL frameworks (built from scratch)
- [Optional] Qiskit or Pennylane for QRL integration

---

## 📎 Dataset

Based on the **Kaggle fraud detection dataset** with synthetic bank transfers and fraud labels.

---

## ▶️ How to Run

```bash
pip install pandas numpy scikit-learn tensorflow
