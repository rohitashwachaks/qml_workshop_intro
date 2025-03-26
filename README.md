## An introduction to QML in PennyLane
- **Author:** Jacob Cybulski ([website](https://jacobcybulski.com/))
- **Collaborators:** Sebastian Zając, Tomasz Rybotycki and Paweł Gora
- **Aims:** To explore the creation and use of simple estimation model in PennyLane.
- **Description:** This Quantum Machine Learning (QML) workshop provides an introduction to Quantum Machine Learning using PennyLane and PyTorch, with hands-on exercises and take-home challenges. The workshop includes four practical sessions that cover the QML concepts, models, and techniques. The sessions explore development of quantum estimators and classifiers, their training with various optimisers, loss and cost functions, as well as model testing and scoring using variety of metrics. It finally, explains how to create hybrid quantum-classical QML models.
- **Structure:** Four sessions over two days, i.e.
  - *Session 1:* QML foundation (basic)
  - *Session 2:* Quantum estimators (intermediate)
  - *Session 3:* Quantum classifiers (intermediate)
  - *Session 4:* Hybrid models (advanced)
- **Start Date:** April, 2025
- **Updates:**
  - v2.0 (Mar 26, 2025): Created

### Important notebooks
- pl_simple_tiny_model_vX_x.ipynb (explains QML principles using PennyLane)
- pl_basic_sin_vX_x.ipynb (creates and executes a very simple quantum estimator)
- pl_medium_qestimator_vX_x.ipynb (creates and executes a more complex quantum estimator)
- utilities.py (various functions used in model development and use)

### Folders
- legacy: previous versions of files dated with the time of their removal
  
### Requirements
- python, version 3.11 or above
- pip install pennylane pennylane-lightning (PennyLane for CPU)
- pip install scikit-learn==1.6.1 pandas==2.2.3 (ML)
- pip install matplotlib==3.10.1 plotly==6.0.0 seaborn==0.13.2 pillow==11.1.0 (plotting and image processing)
- pip install jupyter==1.1.1 jupyterlab==4.3.5 (running jupyter notebooks)
- pip install kagglehub==0.3.10 ucimlrepo==0.0.7 (data access)
- pip install pdflatex (optionally to plot and export some plots and tables to latex)
- install PyTorch [PyTorch](https://pytorch.org/get-started/locally/), as per instructions<br>
  pip install torchsummary torcheval torchmetrics

### License
This project is licensed under the [Creative Commons CC-BY](https://creativecommons.org/licenses/by/4.0/).