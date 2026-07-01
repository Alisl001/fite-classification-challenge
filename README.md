# FITE: Classification Challenge

Welcome to the repository for the FITE Classification Challenge. This project contains the machine learning models and data pipelines developed to solve the classification task.

## 📊 Data Setup

To keep this repository lightweight and fast to clone, the heavy raw datasets are tracked using **Data Version Control (DVC)** and stored in a remote cloud storage. 

### How to Download the Data

To download the datasets, first clone this repository and navigate into the project directory. Then, run `dvc pull` in your terminal to fetch the heavy data files from the remote storage.

**Prerequisites:**
* Ensure you have **Git** installed.
* Ensure you have **DVC** installed (e.g., `pip install dvc`).

**Quick Start Commands:**
```bash
git clone https://github.com/Alisl001/fite-classification-challenge.git
cd fite-classification-challenge
dvc pull
```
