# 3‑D unsteady CPNN prediction of particulate matter transport  

This repository uses a composite neural network (CPNN) to predict the 3‑D particulate matter transport and fate in a hydrodynamic separator under transient loading conditions during a storm event. The CPNN framework details are discussed in the research paper: 
*Operator-based machine learning framework for generalizable prediction of unsteady treatment dynamics in stormwater infrastructure*.

## Quick start

### 1  Prerequisites
| tool | tested version |
|------|---------------|
| **Git** | 2.50+ |
| **Python** | 3.11&nbsp;×64 |
> Windows users: tick **“Add Python to PATH”** when installing Python.

### 2  Clone and set up
```bash
# clone the repo
git clone https://github.com/shatarahhh/CPNN-3D-Unsteady.git
cd CPNN-3D-Unsteady

# create and activate a fresh virtual environment
py -3.11 -m venv .venv          # Linux/macOS: python3 -m venv .venv
source .venv/Scripts/activate   # Linux/macOS: source .venv/bin/activate

# upgrade pip, then install core dependencies
python -m pip install -U pip
pip install -r requirements.txt

# Run the notebook
jupyter notebook
