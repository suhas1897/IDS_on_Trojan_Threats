# IDS on Trojan Threats Using CNN & LSTM Model

## Overview

This project focuses on building an Intrusion Detection System (IDS) to detect Trojan threats using a hybrid model combining Convolutional Neural Networks (CNN) and Long Short-Term Memory (LSTM) networks. The dataset used for training and testing the model is `Trojan_dataset.csv`.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

Intrusion Detection Systems (IDS) are crucial in identifying and preventing malicious activities in a network. This project leverages deep learning techniques, specifically CNN and LSTM, to enhance the detection accuracy of Trojan threats. The CNN component is used for feature extraction, while the LSTM component is utilized for sequence prediction.

## Dataset

The dataset used in this project is `Trojan_dataset.csv`, which contains various features related to network traffic data and labels indicating the presence of a Trojan threat.

### Features

- Network traffic data attributes
- Labels indicating the presence of a Trojan threat

### Source

The dataset is included in the repository.

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/IDS_on_Trojan_Threats.git
   cd IDS_on_Trojan_Threats
python -m venv venv
source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
pip install -r requirements.txt
jupyter notebook IDS_on_Trojan_Threats_Using_CNN_&_LSTM_Model.ipynb

### Additional Files to Include

- `requirements.txt`: List of dependencies required to run the project.
- `LICENSE`: License file for the project.
- `Trojan_dataset.csv`: The dataset file.

### Example `requirements.txt`
```plaintext
numpy
pandas
scikit-learn
tensorflow
keras
matplotlib
jupyter
