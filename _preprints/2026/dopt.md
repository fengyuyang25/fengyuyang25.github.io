---
title: "dOPT: Differentiating Conic Optimization via Geometric Reduction"
date: 2026-09-27
pub: "arXiv preprint"
pub_date: "2026"
cover: /assets/images/covers/dopt.png
authors:
  - Fengyu Yang
  - Connor W. Magoon
  - Tyler Watts
  - Shahar Z. Kovalsky
abstract: >-
  dOPT provides a solver-independent approach to differentiating conic optimization problems. At a computed solution, it constructs a smaller equality-constrained quadratic problem that retains the original solution's first-order sensitivity. Gradients are obtained through one symmetric linear solve, with reductions for convex nonlinear, quadratic, second-order cone, and semidefinite programs. Experiments demonstrate accurate gradients and improved backward-pass scalability.
links:
  Paper: https://arxiv.org/abs/2609.33828
---
