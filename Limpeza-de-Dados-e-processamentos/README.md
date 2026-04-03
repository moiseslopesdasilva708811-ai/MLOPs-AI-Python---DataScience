# 🧠 MLOps Pipeline with Weights & Biases and MLP

This project implements a complete **Machine Learning pipeline** following **MLOps best practices**, using **Weights & Biases (W&B)** for experiment tracking and artifact versioning.

The goal is to build a **reproducible, monitored, and scalable workflow**, covering everything from raw data ingestion to training a **Multi-Layer Perceptron (MLP)** using PyTorch.

---

## 🚀 Features

- 📦 **Artifact Versioning** with Weights & Biases  
  Track datasets, processed data, splits, and trained models

- 🧪 **Data Validation Tests**  
  Automated checks to ensure data consistency and quality

- 🔀 **Train/Test Split with Statistical Validation**  
  Reliable dataset splitting to avoid bias and leakage

- 🧠 **MLP Model (PyTorch)**  
  Implementation of a Multi-Layer Perceptron for supervised learning tasks

- 📊 **Experiment Tracking**  
  Logging of metrics such as loss and performance in real-time using W&B

- ⏹️ **Early Stopping**  
  Prevent overfitting by stopping training when performance stops improving

- 🏆 **Best Model Registration**  
  Automatic saving and versioning of the best-performing model

---

## 🏗️ Pipeline Overview

The pipeline follows a structured MLOps workflow:

1. **Data Ingestion**
   - Load raw dataset
   - Log raw data as an artifact

2. **Data Cleaning & Validation**
   - Handle missing values and inconsistencies
   - Run validation tests

3. **Data Splitting**
   - Train/Test split with statistical checks

4. **Model Training**
   - Train MLP using PyTorch
   - Track metrics with W&B

5. **Model Evaluation**
   - Evaluate performance on test data

6. **Model Registration**
   - Save and version the best model as an artifact

---

## 🛠️ Technologies Used

<p align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytorch/pytorch-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="40" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/jupyter/jupyter-original.svg" width="40" height="40"/>
</p>

---

## 📂 Project Structure

    .
    ├── data/              # Raw and processed datasets
    ├── notebooks/         # Jupyter notebooks
    ├── src/               # Source code (pipeline, models, utils)
    ├── tests/             # Data validation tests
    ├── README.md

---

## ⚙️ Setup

### 1. Clone the repository
    git clone https://github.com/your-username/your-repo.git
    cd your-repo

### 2. Create virtual environment
    python -m venv .venv

### Activate environment:

Windows:
    .venv\Scripts\activate

Linux/Mac:
    source .venv/bin/activate

### 3. Install dependencies
    pip install -r requirements.txt

### 4. Login to Weights & Biases
    wandb login

---

## ▶️ Usage

Run the notebook to execute the full pipeline:

    jupyter notebook

Or execute scripts from the `src/` folder.

---

## 📈 Results

All experiments, metrics, and artifacts are tracked in **Weights & Biases**, enabling:

- Full reproducibility  
- Experiment comparison  
- Model version control  

---

## 🤝 Contributing

Feel free to open issues or submit pull requests to improve this project.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Moisés Lopes**  
Computer Engineering Student | MLOps & AI Enthusiast  

---

## 💡 Final Note

This project demonstrates how to apply **MLOps principles in practice**, making Machine Learning workflows more robust, reproducible, and production-ready.
