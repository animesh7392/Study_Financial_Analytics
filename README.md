# Quantitative Finance, Financial Engineering, Actuarial Science and Insurance
## From First Principles to Practice

A comprehensive, textbook-quality reference covering mathematical foundations through professional-level practice in quantitative finance, financial engineering, actuarial science, and insurance.

## Quick Start

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
2. Click any chapter link in the Table of Contents
3. MathJax and Prism.js are loaded from CDN — internet connection required for first load

## Project Structure

```
textbook/
├── index.html              # Master page: title, TOC, notation table
├── css/
│   └── textbook.css        # Professional stylesheet (print-ready)
├── chapters/               # Individual chapter files
│   ├── ch01_algebra.html
│   ├── ch02_calculus.html
│   ├── ch03_linear_algebra.html
│   ├── ch04_probability.html
│   ├── ch05_distributions.html
│   ├── ch06_statistics.html
│   ├── ch07_stochastic_processes.html
│   ├── ch08_stochastic_calculus.html
│   └── ch09_numerical_methods.html
├── code/                   # Python scripts (by chapter)
├── figures/                # Generated figures (by chapter)
├── data/                   # Sample datasets
├── CHECKLIST.md            # Build progress tracker
└── README.md               # This file
```

## Currently Available

### Part I: Mathematical Foundations (Complete)
- **Ch 1**: Algebra, Functions, Sequences & Series
- **Ch 2**: Calculus (single & multivariable, ODEs)
- **Ch 3**: Linear Algebra (PCA, Cholesky, SVD)
- **Ch 4**: Probability Theory (Bayes, MGFs, CLT)
- **Ch 5**: Probability Distributions (20+ distributions, Panjer class)
- **Ch 6**: Statistics & Inference (MLE, GLM, Bayesian, Bootstrap)
- **Ch 7**: Stochastic Processes (Markov, Poisson, Martingales)
- **Ch 8**: Stochastic Calculus (Itô, GBM, Girsanov, Feynman-Kac)
- **Ch 9**: Numerical Methods & Optimization (Monte Carlo, variance reduction)

### Coming in future parts
- Part II: Financial Theory & Financial Engineering (Ch 10-22)
- Part III: Actuarial Science & Insurance (Ch 23-41)
- Part IV: Integration & Capstones (Ch 42)

### Part V: Dividend Optimizer & Applied Decision Science (New)
- **Ch 43**: Insurance Dividend Policy, Capital Management & Regulatory Framework
- **Ch 44**: Interest Rate Sensitivity Analysis for Insurance
- **Ch 45**: Goal Programming & Multi-Objective Optimization for Finance
- **Ch 46**: Stochastic Programming & Robust Optimization Under Uncertainty
- **Ch 47**: Systems Thinking, Digital Twins & Decision Frameworks
- **Ch 48**: Excel Workshop — Interest Rate Sensitivity & ALM Models
- **Ch 49**: Excel Workshop — Goal Programming & Dividend Optimization
- **Ch 50**: Industry Best Practices in Dividend Optimization

- Appendices A-H

## Technical Details

- **Math rendering**: MathJax 3 (CDN)
- **Code highlighting**: Prism.js (CDN)
- **Typography**: Crimson Pro (body), JetBrains Mono (code), Inter (headings)
- **Print**: A4-ready via `@media print` CSS — use browser Print → Save as PDF

## How to Print to PDF

1. Open a chapter in Chrome
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Select "Save as PDF" as destination
4. Set paper size to A4
5. Check "Background graphics" for color-coded boxes
6. Click Save

## Chapter Structure

Every chapter follows a strict 12-section format:
1. Learning Objectives
2. Prerequisites & Roadmap
3. Intuition & Motivation (real-world story)
4. Formal Theory (definitions, theorems, derivations)
5. Worked Examples (≥3, with realistic numbers)
6. Python Code
7. Diagrams & Charts
8. Common Mistakes & Misconceptions
9. Industry Application Box
10. Summary & Formula Cheat-Sheet
11. Exercises (Basic/Intermediate/Advanced)
12. Further Reading

## License

Educational use. All referenced textbooks and papers are cited with proper attribution.
