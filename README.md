# 🧪 GPU Performance Test: Small Image Classification

This repository contains a Jupyter Notebook that benchmarks GPU performance for small-scale image classification tasks using lightweight neural network models. The goal is to evaluate how efficiently different GPUs handle inference and training when dealing with small-sized images and compact model architectures.

## 📘 Notebook

### [`gpu_performance_test_small_image_classification.ipynb`](./gpu_performance_test_small_image_classification.ipynb)

The notebook includes:

- ✅ **Data Preparation** for small image datasets (e.g., CIFAR-10).
- 🧠 **Model Definition** using lightweight models like MobileNet or custom CNNs.
- ⚙️ **Training and Evaluation** to test performance across CPU and GPU.
- ⏱ **Performance Metrics** including training time, inference speed, and GPU utilization (if applicable).
- 📊 **Visualization** of training accuracy/loss curves and performance comparison.

## 🚀 Getting Started

### Prerequisites

- Python ≥ 3.7
- Jupyter Notebook
- PyTorch or TensorFlow (depending on the framework used in the notebook)
- GPU-enabled environment (e.g., Google Colab, local CUDA-compatible GPU)

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/gpu-performance-test.git
cd gpu-performance-test
```

Create and activate a virtual environment (optional):

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or manually install necessary libraries if no `requirements.txt` is provided:

```bash
pip install torch torchvision matplotlib
```

## 🖼 Example Use Case

This notebook is useful for:

- Comparing GPU acceleration on small model training tasks.
- Understanding the tradeoffs of using compact models on constrained devices.
- Validating GPU speedup for educational or benchmarking purposes.

## 📈 Results

At the end of the notebook, you'll find runtime metrics and visual plots showing training speed and accuracy between CPU and GPU runs.


