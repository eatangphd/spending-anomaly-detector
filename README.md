# 💰 Spending Anomaly Detector

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/spending-anomaly-detector/blob/main/notebooks/anomaly_detection.ipynb)
[![Made with](https://img.shields.io/badge/Made%20with-Jupyter-orange)](https://jupyter.org/)

<div align="center">
  <img src="images/dashboard_preview.png" alt="Dashboard Preview" width="800"/>
  <p><em>Comprehensive visualization dashboard showing spending patterns and detected anomalies</em></p>
</div>

## 📋 Overview

**Spending Anomaly Detector** is a powerful Python tool that analyzes personal financial transactions to identify unusual spending patterns and potential fraud. Using multiple statistical detection methods, it provides visual insights into your spending habits while flagging transactions that deviate from your normal behavior.

### 🎯 Key Features

- **Multi-Method Detection**: Combines Z-score, IQR, and percentile-based approaches
- **Category-Specific Analysis**: Understands normal patterns per expense category
- **Interactive Visualizations**: 9+ comprehensive plots and charts
- **Severity Classification**: Prioritizes anomalies by risk level
- **Exportable Reports**: Generate detailed CSV reports of flagged transactions
- **Google Colab Ready**: Run instantly in your browser without installation

## 🚀 Quick Start

### Option 1: Run in Google Colab (Recommended)

Click the badge below to open the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1YJxIXGxixt0hQvVL3JfOyEB6rkk33rYB?usp=drive_link)

### Option 2: Local Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/spending-anomaly-detector.git
cd spending-anomaly-detector

# Install dependencies
pip install -r requirements.txt

# Run the analysis
jupyter notebook notebooks/anomaly_detection.ipynb
