# QTAP
Quantum Technology Access Programme

Digital Catapult are running the Quantum Technology Access Programme (QTAP) with partners ORCA Computing, Riverlane, 
BT, KETS, and PQ Shield.  

QTAP is part of a wider Innovate UK Industry Strategy Challenge Fund  (ISCF) funded project called Quantum Data Centre 
of the Future which aims to embed a quantum computer within a classical data centre to explore real world access to a quantum computer. 

QTAP aims to engage organisations, raising awareness of the technology and exploring potential quantum computing use cases; providing them with access to the technology and expertise.

This repository contains a series of examples, cases, studies for the QTAP training.  

The linear regression example is based on an example in "Machine Learning for Absolute Beginners"
by Oliver Theobald.

The qiskit examples are based on examples from the [qiskit documentation](https://qiskit.org/documentation/stable/0.28/index.html).  
Please refer to the individual Notebooks for source details.

The material is stored in folders:
- [Python overview](/Python/overview)
- [Excel optimisation excercises](/Excel)
- [Machine learning](/Python/ML)
- [Qiskit](/Python/qiskit)

## Pre-requisites
To run the Jupyter notebooks you must have the following installed:
- Python 3.7 or higher (We recommend installing this using PyEnv or something similar so you do not corrupt your system Python, however this is beyond the scope of this document)
- git

Once you have installed Python, you will need to decide whether to use Anaconda or just install Jupyter notebooks themselves using pip (Beyond the scope of this document)
If you are using pip then please install the following packages:
```
pip3 install --upgrade pip
pip3 install jupyter
```
To run the Machine Learning examples you will need to install
 - [pandas](https://pandas.pydata.org/docs/getting_started/install.html)
 - [numpy](https://numpy.org/install/)
 - [matplotlib](https://matplotlib.org/stable/users/installing/index.html)
 - [scikit-learn](https://scikit-learn.org/stable/install.html)

The clustering example will also require the installation of [Folium](https://pypi.org/project/folium/).  We strongly recommend installing 
Folium in a separate environment using PyEnv or something similar.

To run the qiskit examples you will need to install [qiskit](https://qiskit.org/documentation/stable/0.28/getting_started.html). We strongly 
recommend installing qiskit in a separate environment.

## Installation
Clone the repository to a suitable location on your computer using the following command:
```
git clone https://github.com/digicatapult/QTAP.git

```

## Running the notebooks
To run the notebooks, open a terminal window and navigate to the folder containing the repository.  Then run the following command:

For notebooks in the overview folder
```
jupyter notebook Python/overview/<notebook_name>
```

For notebooks in the Machine Learning folder
```
jupyter notebook Python/ML/<notebook_name>
```

For notebooks in the qiskit folder
```
jupyter notebook Python/qiskit/<notebook_name>
```

## Contributing
If you would like to contribute to this repository, please check our contributing guidelines [here](/CONTRIBUTING.md)