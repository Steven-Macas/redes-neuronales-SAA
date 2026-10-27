<div align="center">

# Neural Networks vs Naive Bayes

**Heart failure and wine quality classification**

<img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python: 3" /> <img src="https://img.shields.io/badge/Pandas-data-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas: data" /> <img src="https://img.shields.io/badge/scikit--learn-ML-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn: ML" /> <img src="https://img.shields.io/badge/TensorFlow-Keras-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow: Keras" />

</div>

## Overview

Two classification problems solved with a **Keras neural network** and compared with **Naive Bayes** models.
The networks use He-uniform initialisation, Adam, `EarlyStopping` and `ReduceLROnPlateau`, and their training
is monitored with `livelossplot`.

| Notebook | Dataset | Naive Bayes | Neural network |
| --- | --- | --- | --- |
| [Heart](https://colab.research.google.com/github/Steven-Macas/redes-neuronales-SAA/blob/main/SSA_stevenMacas_red_neuronal_heart.ipynb) | [Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) | **83.5 %** (Gaussian) | 81.8 % |
| [Wine](https://colab.research.google.com/github/Steven-Macas/redes-neuronales-SAA/blob/main/SSA_stevenMacas_red_neuronal_wine.ipynb) | [Wine Quality](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset) | 50.9 % (Gaussian) · 32.9 % (Multinomial) | **55.5 %** |

Accuracy on the test set. On the heart data the simpler Gaussian Naive Bayes model beats the neural network,
as the notebook's conclusion points out; on the wine data the network wins.

## Results

<table>
  <tr><td align="center" valign="top"><img src="images/heart-confusion-matrix-nb.png" alt="Heart – Gaussian Naive Bayes confusion matrix" width="280" /><br /><sub>Heart – Gaussian Naive Bayes confusion matrix</sub></td><td align="center" valign="top"><img src="images/heart-nn-accuracy.png" alt="Heart – neural network accuracy per epoch" width="280" /><br /><sub>Heart – neural network accuracy per epoch</sub></td><td align="center" valign="top"><img src="images/heart-nn-architecture.png" alt="Heart – network architecture" width="280" /><br /><sub>Heart – network architecture</sub></td></tr>
</table>

*The notebooks are written in Spanish.*

---

<sub>Made by <b>Steven Macas</b> — Data Engineer &amp; Data Analyst · <a href="https://gointy.com">gointy.com</a> · <a href="https://www.linkedin.com/in/steven-macas">LinkedIn</a> · <a href="https://github.com/Steven-Macas">GitHub</a></sub>
