# Gurobi MIP Bounds Tracking with Callback

This repository provides a **Gurobi Code** for tracking **upper and lower bounds** during Mixed-Integer Programming (MIP) optimization. Using **Gurobi's callback**, it collects bound information and plots their evolution in real-time.

## 📊 Features

- ✅ Tracks **upper and lower bounds** for **any MIP problem**.
- ✅ Uses **Gurobi's callback function** to collect bound updates during optimization.
- ✅ **Visualizes** the bound progression with **Matplotlib**.

This is useful for:
- Benchmarking **solution convergence** over time.
- Understanding **how Gurobi improves bounds** during solving.
- Comparing **different MIP models or parameters**.
