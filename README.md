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

## 📚 Reference

The callback mechanism for collecting bounds is inspired by code found in the Gurobi Community Forum:  
🔗 [Working with the optimization log](https://support.gurobi.com/hc/en-us/community/posts/360067833591-Working-with-the-optimization-log)

---

## 🙏 Acknowledgments

Some code snippets used in this repository are adapted from examples provided by **Gurobi Optimization, LLC** (https://www.gurobi.com), and are used here for **educational and research purposes under their terms of use**.

---

## 📜 License

The **original code and models authored in this repository** are released under the [MIT License](LICENSE).  
⚠️ **Note**: Portions adapted from Gurobi's examples are subject to [Gurobi's End User License Agreement (EULA)](https://www.gurobi.com/end-user-license-agreement/).
