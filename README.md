# Neural Networks

Introduction to neural networks with the MATLAB Deep Learning Toolbox, plus an optional exercise in Python with Keras.

> Fourth assignment of the Machine Learning course (1st year, 1st semester), MSc Robotics Engineering, University of Genoa.

## Content

| File | Task |
|---|---|
| `task_0.m` | **Regression:** feed-forward network (10 hidden units, Levenberg-Marquardt) on the body fat dataset |
| `task_1_2.m` | **Classification:** pattern recognition network on the glass dataset, with confusion matrix and ROC curves |
| | **Autoencoder:** 2 hidden units trained on two random MNIST digits, to visualize the 2D encoding of the two classes |
| `optional_task/optional_exercise.ipynb` | **Binary classification** of breast cancer data (Wisconsin dataset) with a Keras MLP (16-8-1, early stopping) |

`loadMNIST.m` and `plotcl.m` are helper functions to load MNIST and plot the encoded classes.

## Usage

- **MATLAB** with the Deep Learning Toolbox: run `task_0.m` and `task_1_2.m`. The body fat and glass datasets are included in the toolbox.
- **Python:** `pip install tensorflow scikit-learn pandas matplotlib seaborn`, then open the notebook in `optional_task/`.
