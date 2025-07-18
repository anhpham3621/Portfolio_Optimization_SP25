# Portfolio Optimization (SP25)
<!-- # = H1, largest heading -->

**Keywords**: Risk Modeling, Linear Programming, Mathematical Optimization, AMPL, Python, Colab, Excel, Matplotlib  
**Summary**: This project develops a simplified, accessible model for portfolio optimization using linear programming to minimize risk while meeting a target return.

---

## Project Status
<!-- ## = H2, second largest heading -->

**Phase 1 (April–May 2025)**  
Initial model development completed by Ramisa Tahsin Rahman, Mariam Fatima, and Anh Pham.  
Special thanks to Dylan Shepardson for early feedback and planning guidance.

**Phase 2 (Ongoing)**  
Enhancements proposed by Anh Pham include:  
- Backtesting using historical data (e.g., 2015–2020 for training, 2020–2025 for evaluation)  
- Evaluation of model assumptions under different market scenarios  
- Benchmarking against real-world data to assess robustness and credibility  

---

## Motivation

In portfolio management, investors aim to achieve target returns while minimizing exposure to risk.  
Total elimination of risk often limits potential returns, so the objective is to strike an optimal balance.

This project applies mathematical optimization to construct a stock portfolio that minimizes overall risk while satisfying return and allocation constraints.

---

## Methodology and Key Results

### Formulation
<!-- ### = H3, smaller heading -->

- Modeled as a Linear Programming (LP) minimization problem  
- Objective: Minimize total portfolio risk  
- Decision variables: investment weights per stock  

### Data and Models

- Data collected from Yahoo Finance and Nasdaq  
- Metrics calculated: return on investment, expected return, variance (risk)  
- Two LP models developed: baseline (budget constraint only) and sector-constrained  

### Results

- Baseline model concentrated investments in 1–2 stocks  
- Sector-constrained model improved diversification with slightly increased risk  
- Trade-off between strict optimality and practical diversification  

---

## Documentation

For more details on Methods,Results, Visualization and Interpretation, Discussion, see the PDF:  
[`Snippet_of_Project_Documentation.pdf`](./Snippet_of_Project_Documentation.pdf)

---

## Tools Used

- `Python`  
- `AMPL`  
- `Google Colab`  
- `NumPy`  
- `Matplotlib`  
- `Excel`  



