# Arritmic3D Notebooks

This repository contains a collection of [Jupyter Notebooks](https://jupyter.org/) examples aimed at training and demonstrating the capabilities of [Arritmic3D](https://commlabuv.github.io/arritmic3d/).

## Contents

- **1.arritmic3d_intro.ipynb**: Basic introduction to the tool and fundamental concepts.
- **2.arritmic3d_models.ipynb**: Exploration of different restitution models and available configurations.
- **3.arritmic3d_blockage.ipynb**: Simulation of conduction blocks and complex dynamics.
- **4.arritmic3d_sensors.ipynb**: How to place sensors and record the temporal evolution of variables at specific tissue points.

## Requirements

To run these notebooks, it is recommended to create a virtual environment and install the necessary dependencies, including the main Arritmic3D library:

```bash
# Create virtual environment (optional but recommended)
python -m venv .venv
source .venv/bin/activate

# Install Jupyter
pip install jupyter
```

## Execution

### Local Execution

Once dependencies are installed, launch Jupyter Notebook from the terminal:

```bash
jupyter notebook
```

This will open a tab in your web browser from which you can explore and execute the examples step-by-step.

### Google Colab

Alternatively, you can run these notebooks directly in the cloud using [Google Colab](https://colab.research.google.com/).
1. Open Google Colab and select **File > Open notebook**.
2. Go to the **GitHub** tab and paste the URL of this repository.
3. Select the notebook you wish to explore.

*Note: When running in Colab, you might need to add a cell at the very beginning of the notebook to install Arritmic3D and its dependencies (e.g., `!pip install ...`) since the Colab environment starts clean.*
