
# HIV Proteinase Docking

This repository contains code and workflows for performing molecular docking of HIV-1 protease with inhibitors using BioExcel Building Blocks (biobb). The primary focus is to demonstrate how molecular docking can be used to analyze the interaction between HIV-1 protease and potential inhibitors.

## Project Overview

The aim of this project is to automate the process of setting up docking simulations and analyzing binding interactions using biobb libraries. The docking is performed using the protein structure of HIV-1 protease and a known inhibitor, Saquinavir (Ligand code: MK1).

Key features of the project:
- Prepares protein and ligand structures for docking.
- Conducts docking simulations using AutoDock Vina.
- Analyzes the docking results to determine binding interactions and affinity.

## Requirements

To run this project, you need the following dependencies installed:

- Python 3.8+
- BioExcel Building Blocks (biobb)
- AutoDock Vina
- Numpy
- Matplotlib
- Jupyter Notebook

You can install the required dependencies with the following command:

```
pip install -r requirements.txt
```

## Usage

1. Clone the repository:

```
git clone https://github.com/Jencheng1/HIVProteinaseDocking.git
cd HIVProteinaseDocking
```

2. Run the Jupyter notebook:

```
jupyter notebook HIVProteaseInhibitorDocking.ipynb
```

Alternatively, you can run this notebook on Google Colab by uploading the `HIVProteaseInhibitorDocking.ipynb` file to your Colab environment. This allows the execution of the docking simulations and analysis without the need to install anything locally.

## Data

- **Protein**: HIV-1 protease (PDB Code: 1HVR)
- **Ligand**: Saquinavir (Ligand Code: MK1)

These structures are retrieved and prepared using the biobb modules.

## Credit

This project leverages the **BioExcel Building Blocks (biobb)**, which provides the essential components for building molecular dynamics workflows in Python. For more information on biobb, please visit BioExcel Building Blocks at https://biobb-common.readthedocs.io/en/latest/.

## License

This project is licensed under the MIT License - see the LICENSE file at the following link for details: https://www.mit.edu/~amini/LICENSE.md.

