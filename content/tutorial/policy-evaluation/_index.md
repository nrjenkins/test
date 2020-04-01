---
# Course title, summary, and position.
linktitle: Intro to Policy Evalution with R
summary: Learn the basics of conducting a policy evaluation project using R.
weight: 1

# Page metadata.
title: Overview
date: "2018-09-09T00:00:00Z"
lastmod: "2018-09-09T00:00:00Z"
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.

# Add menu entry to sidebar.
# - name: Declare this menu item as a parent with ID `name`.
# - weight: Position of link in menu.
menu:
  example:
    name: Overview
    weight: 1
---

## Bayesian Inference with Stan

In this series of tutorials, I will show you how to use Stan to program hierarchical models. These tutorials will follow the chapters in [Bayesian Hierarchical Models](https://www.amazon.com/Bayesian-Hierarchical-Models-Applications-Second/dp/1498785751) written by Peter D. Congdon.

Rather than focus on the mathematical details of bayesian inference, these tutorials will mostly focus on their implementation in Stan.

[Stan](https://mc-stan.org) is a programming language for bayesian inference that uses Hamiltonian Monte Carlo sampling. Hamiltonian Monte Carlo (HMC) sampling uses on gradian evaluation to sample from the posterior which is much more efficient than other sampling methods like Metropolis-Hastings and Gibbs sampling. As a result, HMC can achieve convergence much faster than these alternative samplers.
