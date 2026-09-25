# Battery-Aware Task Scheduler Simulator

A lightweight Python event-loop simulation modeling an edge device resource manager that dynamically balances computation tasks between local processing and cloud offloading[cite: 1, 2].

## Overview

In low-power edge computing systems, optimizing energy consumption is critical[cite: 1, 2]. This project implements a policy-driven decision engine that:
1. **Tracks real-time battery drain curves** under varying power profiles.
2. **Monitors synthetic CPU workload thresholds** to evaluate system stress.
3. **Optimizes task placement** by choosing local execution when power is abundant versus cloud offloading when battery levels drop or CPU limits are saturated.
4. **Visualizes power profiles and decision convergence** across discrete temporal steps.

## Code Architecture

* **Dependencies:** `numpy`, `matplotlib`
* **Core Logic:** Threshold-based dynamic control system simulating edge-cloud collaboration.
* **Environment:** Designed for rapid prototyping and visualization in Google Colab.

## Results & Visualization

When executed, the simulator outputs operational metrics and renders a two-panel performance diagram:
* **Top Panel:** Traces battery depletion alongside fluctuations in synthetic CPU workloads against defined critical thresholds.
* **Bottom Panel:** Plots the discrete scheduler decisions over time, contrasting local execution cycles against cloud offloading transitions.

## How to Run

You can view and execute this notebook directly in Google Colab:
https://colab.research.google.com/drive/10MRQ-kAsj0HhQTV_eeqMy6og88l6EQ3E?usp=sharing 

Maryam Fagbo
