# CISE-AMGNN
## Description

This project requires **Python 3.7** and a specific set of Python packages to run correctly. Please follow the instructions below to set up your environment.

## Environment Setup

### 1. Python Version

Make sure you are using **Python 3.7**. You can create a virtual environment using `conda`:

```bash
conda create -n myenv python=3.7
conda activate myenv
python3.7 -m venv myenv
source myenv/bin/activate  # On Windows use `myenv\Scripts\activate`

### 2. Install Dependencies

To install the core dependencies, run:

```bash
pip install \
  numpy==1.21.6 \
  scipy==1.7.3 \
  pandas==1.3.5 \
  matplotlib==3.5.3 \
  scikit-learn==1.0.2 \
  torch==1.13.1 \
  torchvision==0.14.1 \
  torchtext==0.5.0 \
  torch-geometric==2.3.1 \
  dgl-cu92==0.6.1 \
  rdkit==2023.3.2 \
  rdkit-pypi==2022.9.5 \
  openbabel-wheel==3.1.1.20 \
  pymatgen==2022.0.17 \
  matminer==0.8.0 \
  MolScribe==1.1.1 \
  SmilesPE==0.0.3 \
  umap-learn==0.5.7

