# Introduction to Deep Learning & Neural Networks Repository

This repository contains Jupyter notebooks and resources for learning the basics of deep learning and neural networks. The materials cover key concepts including Artificial Neural Networks (ANNs), Regression Neural Networks, Classification Neural Networks, and Convolutional Neural Networks (CNNs).

## Table of Contents

- [Directory Structure](#directory-structure)
- [Detailed Overview](#detailed-overview)
  - [Jupyter Notebooks](#jupyter-notebooks)
  - [Assets](#assets)
  - [Requirements](#requirements)
- [Getting Started](#getting-started)
- [Command to Create Executable](#command-to-create-executable)

## Directory Structure

- **Jupyter Notebooks**
  - `1- Introduction to ANN.ipynb`: Introduction to Artificial Neural Networks.
  - `2- Regression NN.ipynb`: Implementation of a regression model using neural networks.
  - `3- Classification NN.ipynb`: Implementation of a classification model using neural networks.
  - `4- CNN.ipynb`: Introduction to Convolutional Neural Networks (CNNs).

- **Assets**
  - `classification_model.h5`: Pre-trained classification model.
  - `concrete_data.csv`: Dataset used in one of the notebooks for regression.
  - `.gitignore`: Specifies files to ignore when using Git version control.
  - `Build a Regression Model in Keras/`: Directory containing additional resources or exercises related to building a regression model in Keras.

## Detailed Overview

### Jupyter Notebooks

1. **1- Introduction to ANN.ipynb**: This notebook provides an overview of Artificial Neural Networks (ANNs), including their architecture, working mechanisms, and how to implement a basic ANN using Python and Keras.

2. **2- Regression NN.ipynb**: Learn how to build and train a neural network for a regression task. This notebook explains how to preprocess data, design a network architecture, and train the model to predict continuous values.

3. **3- Classification NN.ipynb**: This notebook covers the implementation of a neural network for classification tasks, explaining how to train a model to categorize data into different classes using labeled datasets.

4. **4- CNN.ipynb**: An introduction to Convolutional Neural Networks (CNNs). This notebook explains how CNNs are used primarily for image classification, and guides you through building a simple CNN model.

### Assets

1. **classification_model.h5**: This file contains a pre-trained model that can be used to demonstrate how to save, load, and use a neural network for classification.

2. **concrete_data.csv**: A dataset used for building a regression model. This dataset contains features related to concrete compressive strength.

3. **.gitignore**: A configuration file used to specify which files and directories should be ignored by Git. This helps avoid tracking unnecessary files, such as temporary files or virtual environments.

4. **Build a Regression Model in Keras/**: This directory may contain additional exercises or practical examples related to building regression models using Keras, a popular deep learning framework.

## Getting Started

To explore the notebooks, make sure you have Python and Jupyter Notebook installed. You can install the required dependencies using:

```sh
pip install -r requirements.txt
```

After installing the dependencies, you can start Jupyter Notebook with:

```sh
jupyter notebook
```

Navigate to the desired notebook to start learning.

## Command to Create Executable

If you want to create an executable for any of the Python scripts, use the following command:

```sh
pyinstaller -F -w -i icon.ico script_name.py
```

Replace `script_name.py` with the name of the script you wish to convert.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries are specified in the notebooks, typically at the top with `import` statements.
