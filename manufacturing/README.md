# Evaluate a Manufacturing Process

This project applies **statistical process control (SPC)** techniques to manufacturing data to identify whether a process is operating within acceptable limits.

The goal is to help a manufacturing team monitor and improve quality by analyzing measurements such as item height and detecting when adjustments are needed.

## ⚙️ Project Overview

- Uses SQL window functions and nested queries to analyze production data
- Calculates control limits:
  - **UCL**: `avg_height + 3 * stddev_height / sqrt(5)`
  - **LCL**: `avg_height - 3 * stddev_height / sqrt(5)`
- Identifies parts that fall outside acceptable limits
- Helps ensure a stable, high-quality manufacturing process

## 🧰 Tools
- SQL
- Window functions and aggregations
- Jupyter Notebook (SQL interface)