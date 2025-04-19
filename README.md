# Semi-Supervised Anomaly Detection using DevNet

This project implements **DevNet**, a deep learning-based approach for **semi-supervised anomaly detection**. It allows training models with a large amount of normal data and a small number of known outliers, simulating real-world conditions.

## 🚀 Features

- Deep neural network for learning anomaly scores
- Semi-supervised setup: uses mostly normal data + limited labeled anomalies
- Customizable number of known outliers using the `--known_outliers` flag
- Supports multiple datasets for experimentation


## ⚙️ How It Works

- The model is trained on mostly **normal data**.
- Only a small number of **known outliers** are included using the `--known_outliers` argument.
- This helps simulate real-world scenarios where only a few anomalies are labeled.

Example:

```bash
python main.py
