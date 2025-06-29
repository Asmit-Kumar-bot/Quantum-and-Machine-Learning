
# 🧪 Quantum ML for Molecular Property Prediction

This project explores **Quantum Machine Learning** (QML) techniques for **molecular property classification**. It uses **VQE (Variational Quantum Eigensolver)** to extract quantum features and evaluates models using both **quantum support vector classifiers (QSVC)** and classical algorithms like **SVC** and **Random Forest**.

---

## 📌 Project Highlights

- ✅ **Quantum Feature Generation** using VQE
- ✅ **Custom Hamiltonian construction** for H₂-like molecules
- ✅ Classification using:
  - QSVC (Quantum SVM)
  - SVC (Classical SVM)
  - Random Forest
- ✅ Performance comparison between classical and quantum models

---

## ⚙️ Technologies & Libraries Used

- 🧠 `Qiskit` – for quantum computing and VQE
- 📊 `Qiskit Machine Learning` – QSVC & quantum kernels
- 🧮 `Scikit-learn` – for classical ML (SVC, RandomForest)
- 📈 `NumPy` – numerical computation

---

## 🧬 What Is VQE?

**VQE (Variational Quantum Eigensolver)** is a hybrid quantum-classical algorithm used to estimate the ground state energy of a molecule. In this project, VQE acts as a **feature generator** to create input features based on parameterized Hamiltonians.

---

## 🧠 What Is QSVC?

**QSVC (Quantum Support Vector Classifier)** is a quantum-enhanced classifier that uses **quantum kernels** to map data into a high-dimensional Hilbert space, leveraging quantum properties to find complex decision boundaries.

---

## 🧪 Dataset Generation Process

1. **Custom Hamiltonian**: A simple qubit Hamiltonian simulating H₂ is defined using Pauli operators.
2. **VQE Calculation**: Ground state energy is computed using VQE with varying bond-length parameters.
3. **Feature Creation**: Energies are used as features, with labels assigned to different value ranges.

---

## 🏗️ Project Structure

```
.
├── quantum_ml_molecular_prediction.ipynb  # Main notebook
├── README.md                              # You are here!
```

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Asmit-Kumar-bot/Quantum-and-Machine-Learning
   cd Quantum-and-Machine-Learning
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook:
   ```bash
   jupyter notebook quantum_ml_molecular_prediction.ipynb
   ```

---

## 📊 Results

The project compares accuracy of three classifiers:

| Model           | Accuracy |
|----------------|----------|
| QSVC (Quantum) | ~        |
| SVC (Classical)| ~        |
| Random Forest  | ~        |

*You can replace these with your actual accuracy values from the notebook run.*

---

## 🧠 Concepts You’ll Learn

- Quantum circuits and Pauli operators
- Variational quantum algorithms
- Feature extraction via VQE
- Classical vs quantum ML model comparison

---
