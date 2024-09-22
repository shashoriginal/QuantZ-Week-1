
# Week 1: Advanced Mathematical Concepts in Quantitative Finance

This repository contains the materials from Week 1 of the QuantZ initiative, which covers key advanced mathematical concepts applied in quantitative finance. The content is structured into two major parts: **Foundations of Calculus and Linear Algebra** and a **Simulation of the Optiver Balloon Blowing Test**, providing both theoretical insights and practical Python-based examples for students and professionals aiming to excel in quantitative finance.

## Table of Contents

1. [Overview](#overview)
2. [Topics Covered](#topics-covered)
3. [Notebook Details](#notebook-details)
4. [Setup Instructions](#setup-instructions)
5. [Dependencies](#dependencies)
6. [Challenging Problems](#challenging-problems)
7. [Simulation: Optiver Balloon Blowing Test](#simulation-optiver-balloon-blowing-test)
8. [Contributing](#contributing)
9. [License](#license)
10. [Author](#author)

## Overview

This project dives into advanced concepts in **multivariable calculus**, **linear algebra**, and their applications in finance. It also includes an interesting interactive simulation, the **Optiver Balloon Blowing Test**, which evaluates decision-making under risk. The repository is designed for both beginners and those with a strong mathematical background interested in applying theoretical concepts to quantitative finance problems.

## Topics Covered

1. **Calculus**: Understanding derivatives and integrals with real-world finance examples (e.g., stock price fluctuations and revenue curves).
2. **Linear Algebra**: Introduction to vectors, matrices, matrix operations, inverses, determinants, and their financial applications.
3. **Multivariable Calculus**: Partial derivatives, gradient vectors, and optimization in financial contexts.
4. **Eigenvalues and Eigenvectors**: Investigating the stability of financial systems using matrix-based models.

## Notebook Details

### `Week1_(QuantZ).ipynb`

The Jupyter Notebook provides both theory and practical examples, structured as follows:

- **Part 1: Review and Foundations** (30 minutes)
  - Basic Calculus (Derivatives and Integrals)
  - Introduction to Linear Algebra (Vectors and Matrices)
  
- **Part 2: Diving Deeper into Linear Algebra** (30 minutes)
  - Matrix Operations (Multiplication, Inverses, and Determinants)
  - Solving Linear Systems
  - Eigenvalues and Eigenvectors

- **Challenging Problems**
  - Financial stability using eigenvalues
  - Maximizing profit strategy via matrix operations
  - Solving transaction systems with matrix inversions

## Setup Instructions

To run this project, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/username/repo-name.git
cd repo-name
```

### 2. Create a Virtual Environment (Optional but Recommended)

```bash
python3 -m venv venv
source venv/bin/activate  # For Windows: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebook `Week1_(QuantZ).ipynb` to explore the content.

## Dependencies

This project requires the following Python libraries:

- `numpy`
- `scipy`
- `sympy`
- `matplotlib`
- `ipywidgets`
- `jupyter`

To install the dependencies, run:

```bash
pip install -r requirements.txt
```

## Challenging Problems

1. **Financial Stability Investigation**: 
   - Investigate the stability of a portfolio by calculating eigenvalues of the asset relationship matrix.
  
2. **Maximum Profit Strategy**: 
   - Use matrix operations to find the optimal strategy that maximizes profit under specific constraints.
  
3. **Unravel Financial Transactions**: 
   - Use matrix inversion to determine original transaction amounts from a matrix describing financial transactions between accounts.

## Simulation: Optiver Balloon Blowing Test

The Optiver Balloon Blowing Test simulation is a decision-making game that challenges users to balance risk and reward. You can interact with this simulation in the notebook.

### Key Features:
- **Pumping**: Inflate the balloon to increase potential earnings.
- **Collecting**: Secure your earnings before the balloon bursts.
- **Risk Evaluation**: Balancing greed with caution to maximize total earnings.

### What the Test Evaluates:
- **Risk Management**: How well the player manages risk and balances it with potential rewards.
- **Decision-Making Under Uncertainty**: Decisions must be made without knowing when the balloon will burst, simulating real-world uncertainty.
- **Strategic Thinking**: Players are rewarded for making calculated decisions to optimize profits.
- **Loss Aversion**: The test measures how players react to losses and adapt their strategy over time.

### How to Play

To launch the simulation, run the cell block labeled **Optiver Balloon Blowing Test Simulation** in the notebook.

## Contributing

We welcome contributions to improve the content and functionality of this project! Please submit a pull request with your changes, ensuring that your code follows the project’s guidelines.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

**Shashank Raj**  
*President and Controller at QuantZ MSU*  
[LinkedIn](https://www.linkedin.com/in/rshashank10/) 
[Instagram](https://www.instagram.com/shashoriginal/)
