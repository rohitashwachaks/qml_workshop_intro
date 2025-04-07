## An introduction to QML in PennyLane (PL) and PyTorch
- **Author:** [Jacob Cybulski](https://jacobcybulski.com/) ([LinkedIn](https://www.linkedin.com/in/jacobcybulski/)), *Enquanted*
- **Collaboration with:**
      [Sebastian Zając](https://sebastianzajac.pl/) ([LinkedIn](https://www.linkedin.com/in/sebastianzajac/)),
      Tomasz Rybotycki ([LinkedIn](https://www.linkedin.com/in/tomasz-rybotycki-01192582/)) and
      Paweł Gora ([LinkedIn](https://www.linkedin.com/in/pawelgora/))
- **Associated with:** [QPoland](https://qworld.net/qpoland/) and [Quantum AI Foundation](https://www.qaif.org/)
- **Aims:** To explore the creation and use of quantum machine learning models in PennyLane and PyTorch.
- **Description:** This Quantum Machine Learning (QML) workshop provides an introduction to Quantum Machine Learning using PennyLane and PyTorch, with hands-on exercises and take-home challenges. The workshop includes four practical sessions that cover the QML concepts, models, and techniques. The sessions explore development of quantum estimators and classifiers, their training with various optimisers, loss and cost functions, as well as model testing and scoring using variety of metrics. It finally, explains how to create hybrid quantum-classical QML models.
- **Structure:** Four sessions over two days, i.e.
  - _**Session 1:**_ QML foundation (basic)
  - _**Session 2:**_ Quantum estimators (intermediate)
  - _**Session 3:**_ Quantum classifiers (intermediate)
  - _**Session 4:**_ Hybrid models (advanced)
- **Release Date:**
  - _**April, 11 2025:**_ The final versions will be made available 1 day before the workshop
- **Last Update:**
  - _**April 06, 2025:**_ Sessions 1-4 completed, all challenges added, sample answers after sessions
  - _**April 07, 2025:**_ Small updates (README)

### Important notebooks

You can play with these notebooks, enjoy!<br>
Note however that they may be updated at any time!

| Session | File | Description |
| :- | :- | :- |
| *Explore&nbsp;1* | s00_explore_tiny_model_vX_x.ipynb | Explains QML principles using PL |
| *Explore&nbsp;2* | s00_explore_meas_tests_vX_x.ipynb | Explains data encoding and measurements in PL |
|  |  |  |
| *Session&nbsp;1* | s01_simple_model_vX_x.ipynb | Creates and tests a very simple quantum model |
| *Session&nbsp;2* | s02_medium_qestimator_vX_x.ipynb | Creates and tests a more complex quantum estimator |
| *Session&nbsp;3* | s03_medium_qclassifier_vX_x.ipynb | (creates and tests a quantum classifier |
|  | s03_medium_cclassifier_vX_x.ipynb | Creates and tests a classical classifier |
| *Session&nbsp;4* | s04_advanced_hybrid_vX_x.ipynb | Creates and tests a quantum-classical hybrid model |
|  | s04_challenge_qreservoir_vX_x.ipynb | Hard challenge to create a PyTorch quantum reservoir |
|  | s04_challenge_creservoir_vX_x.ipynb | Reference for the challenge - classical reservoir in Python |
|  |  |  |
| *Other* | utilities.py | A number of useful plotting functions to make your life easier |
| | requirements.txt | A list of software needed for this workshop (for auto-install with *pip*) |

### Folders
- _**images:**_ some images appearing in notebooks (via a relative link)
- _**legacy:**_ previous versions of files (in case you really really wanted them)
- _**slides:**_ presentation slides in PDF (as they become available)
  
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

The **requirements.txt** file was tested for the environment installation on 
Ubuntu 22.04-24.04, Windows 11 and MacOS Sequoia 15.3.1 (with M3 procesor).

### License
This project is licensed under the [GNU General Public License v3](./LICENSE).
The GPL v3 license requires attribution for modifications and derivatives, ensuring that users know which versions are changed and to protect the reputations of original authors.