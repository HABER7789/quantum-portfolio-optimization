# Quantum Portfolio Optimization Research

This repository contains research on portfolio optimization using quantum computing approaches, specifically implementing and comparing Variational Quantum Eigensolver (VQE) and Quantum Approximate Optimization Algorithm (QAOA) methods.

## Overview

The project implements quantum approaches to portfolio optimization using Google's Cirq framework. It compares different methods:
- Classical portfolio optimization
- VQE-based optimization
- QAOA-based optimization

## Features

- Implementation of VQE and QAOA circuits for portfolio optimization
- Comparison of classical vs quantum approaches
- Performance metrics including returns, risk, and Sharpe ratios
- Visualization of portfolio weights and performance metrics
- Extensible framework for testing different quantum optimization strategies

## Requirements

The project requires the following Python packages:
- cirq
- sympy
- numpy
- matplotlib
- plotly
- typing

## Installation

1. Clone this repository:
```bash
git clone https://github.com/yourusername/quantum-portfolio-optimization.git
cd quantum-portfolio-optimization
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

The main research implementation is in the Jupyter notebook `QCFinanceResearch.ipynb`. To run it:

1. Start Jupyter Lab or Notebook:
```bash
jupyter lab
```

2. Open `QCFinanceResearch.ipynb`
3. Run all cells to see the comparison of different optimization approaches

## Results

The implementation compares three approaches:
1. Classical optimization (equal weights)
2. VQE optimization
3. QAOA optimization

Key findings show that:
- VQE tends to find more concentrated portfolios
- QAOA produces intermediate concentration levels
- Each method has different trade-offs in terms of returns, risk, and computation time

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Citation

If you use this code in your research, please cite:

```bibtex
@software{quantum_portfolio_optimization,
  author = {Dhairya Patel},
  title = {Quantum Portfolio Optimization Research},
  year = {2024},
  publisher = {GitHub},
  url = {https://github.com/yourusername/quantum-portfolio-optimization}
}
```
