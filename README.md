
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

## Screenshots

**Binding Site Structure (Ligand)**
![Screenshot 2024-10-14 at 9 58 29 PM](https://github.com/user-attachments/assets/b2d85c89-b1af-4ff5-88cc-3ec8e694a6af)

![Screenshot 2024-10-14 at 9 58 40 PM](https://github.com/user-attachments/assets/371969dc-e7da-4a1e-8f6f-e38d352b4c76)

**Binding Site Structure (Small Molecule)**
![Screenshot 2024-10-14 at 9 59 02 PM](https://github.com/user-attachments/assets/010beb62-20c1-41fc-8fcb-e990cd5e1dbe)


**Binding Site Structure with LigandsBox, LinesBox, and Residues**
![Screenshot 2024-10-14 at 9 59 26 PM](https://github.com/user-attachments/assets/111ebb10-d35c-4c44-8764-d561f04df21f)


**Ligand and Prep-Ligand Orientation**
![Screenshot 2024-10-14 at 9 59 41 PM](https://github.com/user-attachments/assets/6bf8ea07-9afa-4848-afba-e47a317b30e6)

**Hydrogen Charge Pattern with Licorice and Ball+Stick**
![Screenshot 2024-10-14 at 10 00 26 PM](https://github.com/user-attachments/assets/8fd1c16e-59da-463d-8bae-8e6748c55b42)


**Docking Simulation Result**
![Screenshot 2024-10-14 at 10 01 00 PM](https://github.com/user-attachments/assets/504d95cd-9e0c-4d77-b295-ebf35212289d)

![Screenshot 2024-10-14 at 10 02 19 PM](https://github.com/user-attachments/assets/d01b9446-63b6-4ab1-b70a-2ddceadaad79)

![Screenshot 2024-10-14 at 10 02 37 PM](https://github.com/user-attachments/assets/cd1cfb31-be20-4f26-880a-e67689546306)



