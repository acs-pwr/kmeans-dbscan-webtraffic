# kmeans-dbscan-webtraffic
compare performance between kmeans and dbscan in web traffic dataset


# Dataset

The dataset used in this project is from Kaggle: [Cybersecurity: Suspicious Web Threat Interactions](https://www.kaggle.com/datasets/jancsg/cybersecurity-suspicious-web-threat-interactions).

Download the dataset from Kaggle and place the `CloudWatch_Traffic_Web_Attack.csv` file in the same directory as the notebook.

# Installation Guide

This guide will help you set up the environment to run the `bytes-diff-vs-src-ip.ipynb` notebook.

## Prerequisites

- Python 3.10 or higher
- Jupyter Notebook

## Steps
### 1. Clone the Repository

First, clone the repository to your local machine:
```sh
git clone https://github.com/yourusername/kmeans-dbscan-webtraffic.git
cd kmeans-dbscan-webtraffic
```


### 2. Create a Virtual Environment
Create a virtual environment to manage dependencies:
``` sh
python -m venv .venv
```

Activate the virtual environment:
On Windows:
``` sh
.venv\Scripts\activate
```
On macOS and Linux:
``` sh
source .venv/bin/activate
```

### 3. Install Dependencies
Install the required Python packages:
``` sh
pip install pandas scikit-learn matplotlib seaborn jupyter
```

### 4. Run Jupyter Notebook
Start the Jupyter Notebook server:
``` sh
jupyter notebook
```
