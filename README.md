# PennyLane Quantum Computing Portfolio

![Python](https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PennyLane](https://img.shields.io/badge/PennyLane-0.35+-6C5CE7?style=for-the-badge&logo=pennylane&logoColor=white)

A repository combining lecture notes and presentation code from an intensive summer quantum computing course alongside self-completed algorithmic challenges from the official PennyLane platform.

---

## 📁 Repository Structure

```text
.
├── lessons/          # Course presentation notes & lecture code from Summer Quantum Program
├── challenges/       # Independently solved problem sets from PennyLane's official website
├── requirements.txt  # Project dependencies
└── README.md
```

---

## 🧠 Content Overview

### 📚 `/lessons` (Course Notes & Lectures)
Lecture materials, code walkthroughs, and presentation concepts from the summer course:
* **PennyLane 101**: Introductory quantum mechanics concepts, circuit construction, and basic state preparation.
* **PennyLane 102**: Parameterized quantum circuits, quantum gradients, and differentiable QNode optimization.
* **Decoded Quantum Interferometry (DQI)**: Formulating combinatorial optimization through quantum state encoding and dual-code error decoding.

### 🎯 `/challenges` (Independent Solutions)
Solutions written independently for coding challenges hosted on the official PennyLane platform:
* **Variational Quantum Eigensolver (VQE)**: Estimating ground-state molecular energies.
* **Quantum Fourier Transform (QFT)**: Implementing phase estimation routines and quantum circuit adders.

---

## 🛠️ Tech Stack

* **Quantum Framework**: [PennyLane](https://pennylane.ai/)
* **Language**: Python 3.9+
* **Execution Backends**: `default.qubit`, `lightning.qubit`
* **Scientific Computing**: NumPy, SciPy, Matplotlib

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/pennylane-portfolio.git](https://github.com/your-username/pennylane-portfolio.git)
   cd pennylane-portfolio
   ```

2. **Set up a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**:
   ```bash
   pip install pennylane numpy matplotlib
   ```

---

## 📜 Attribution

* **Lessons**: Code and materials in `/lessons` originated as presentation materials from the summer course curriculum.
* **Challenges**: All challenge implementations in `/challenges` are original solutions written independently.
