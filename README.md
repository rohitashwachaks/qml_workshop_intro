## An introduction to QML in PennyLane (PL)
- **Author:** [Jacob Cybulski](https://jacobcybulski.com/) ([LinkedIn](https://www.linkedin.com/in/jacobcybulski/)), *Enquanted*
- **Collaboration with:**
      [Sebastian Zając](https://sebastianzajac.pl/) ([LinkedIn](https://www.linkedin.com/in/sebastianzajac/)),
      Tomasz Rybotycki ([LinkedIn](https://www.linkedin.com/in/tomasz-rybotycki-01192582/)) and
      Paweł Gora ([LinkedIn](https://www.linkedin.com/in/pawelgora/))
- **Associated with:** [QPoland](https://qworld.net/qpoland/) and [Quantum AI Foundation](https://www.qaif.org/)
- **Aims:** To explore the creation and use of simple estimation model in PennyLane.
- **Description:** This Quantum Machine Learning (QML) workshop provides an introduction to Quantum Machine Learning using PennyLane and PyTorch, with hands-on exercises and take-home challenges. The workshop includes four practical sessions that cover the QML concepts, models, and techniques. The sessions explore development of quantum estimators and classifiers, their training with various optimisers, loss and cost functions, as well as model testing and scoring using variety of metrics. It finally, explains how to create hybrid quantum-classical QML models.
- **Structure:** Four sessions over two days, i.e.
  - *Session 1:* QML foundation (basic)
  - *Session 2:* Quantum estimators (intermediate)
  - *Session 3:* Quantum classifiers (intermediate)
  - *Session 4:* Hybrid models (advanced)
- **Release Date:**
  - April, 11 2025
- **Last Update:**
  - Apr 01, 2025 - Session 4 challenge added (draft)

### Important notebooks

<!--You can play with these notebooks, enjoy!-->
These notebooks are currently in development - please do not use them!

| Session | File | Description |
| :-: | :- | :- |
| *Explore 1* | pl_explore_tiny_model_vX_x.ipynb | (explains QML principles using PL) |
| *Explore 2* | pl_explore_meas_tests_vX_x.ipynb | (explains data encoding and measurements in PL) |
|  |  |  |
| *Session 1* | pl_simple_model_vX_x.ipynb | (creates and tests a very simple quantum model) |
| *Session 2* | pl_medium_qestimator_vX_x.ipynb | (creates and tests a more complex quantum estimator) |
| *Session 3* | pl_medium_qclassifier_vX_x.ipynb | (creates and tests a quantum classifier) |
|  | pl_medium_cclassifier_vX_x.ipynb | (creates and tests a classical classifier) |
| *Session 4* | pl_advanced_hybrid_vX_x.ipynb | (creates and tests a quantum-classical hybrid model) |
|  | pl_advanced_qreservoir_vX_x.ipynb | (hard challenge to create a PyTorch quantum reservoir) |
|  | pl_advanced_creservoir_vX_x.ipynb | (reference for the challenge - classical reservoir in Python) |

### Folders
- legacy: previous versions of files dated with the time of their removal
  
### Requirements
_See the **requirements.txt** file, load with **pip install -r requirements.txt**._
- Set up a virtual environment with venv or anaconda for Python 3.11, open it and install...
- pip install pennylane==0.40.0 pennylane-lightning==0.40.0 (PennyLane for CPU)
- pip install scikit-learn==1.6.1 pandas==2.2.3 (ML)
- pip install matplotlib==3.10.1 plotly==6.0.0 seaborn==0.13.2 pillow==11.1.0 (plotting and image processing)
- pip install jupyter==1.1.1 jupyterlab==4.3.5 (running jupyter notebooks)
- pip install kagglehub==0.3.10 ucimlrepo==0.0.7 (data access)
- pip install pdflatex (optionally to plot and export some plots and tables to latex)
- install [PyTorch](https://pytorch.org/get-started/locally/), as per web site instructions, also add:<br>
  pip install torchsummary torcheval torchmetrics

### License
This project is licensed under the [Creative Commons CC-BY](https://creativecommons.org/licenses/by/4.0/).