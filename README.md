
# 📊 Mean-Variance-Standard-Deviation Calculator

This project contains a Python module that uses **NumPy** to perform statistical calculations on a 3x3 matrix. Given a list of **nine** numbers, it calculates the **mean**, **variance**, **standard deviation**, **maximum**, **minimum**, and **sum** across the matrix's **rows**, **columns**, and **flattened data**.

---

## 📁 Project Files

- `mean_var_std.py` – Contains the main `calculate()` function.
- `main.py` – A simple script to manually test the function.
- `test_module.py` – Unit tests to verify correctness.

---

## 📌 Function Description

### `calculate(input_list: list) -> dict`

- **Input**: A list of **9 numerical values**.
- **Output**: A dictionary with statistical results:
  - Along **axis 0** (columns)
  - Along **axis 1** (rows)
  - Across the **entire matrix**

If the list contains fewer or more than 9 numbers, a `ValueError` is raised:

