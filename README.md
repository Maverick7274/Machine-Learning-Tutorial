# Tutorials for Machine Learning and Data Science

This repository contains tutorials for machine learning and data science. The tutorials are written in Jupyter Notebook and can be run in VS Code.

## Setup VS Code

1. Install VS Code

2. Install Python extension for VS Code

3. Install Jupyter extension for VS Code

4. Install Anaconda from [here](https://www.anaconda.com/products/individual)

5. Create a new conda environment

```bash
conda create --prefix ./venv pip tensorflow
```

6. Activate the conda environment

```bash
conda activate {absolute/path}/venv
```

> TIP : You can use `conda config --set env_prompt '({name})'` to show the current name of the conda environment in the terminal instead of the absolute path.


# Setup Jupyter Notebook in VS Code

## Install Jupyter Notebook

1. Install Python 3.6 or higher

2. Install Jupyter Notebook

```bash
pip install jupyter
```

3. Install Jupyter Notebook extension for VS Code

4. Open VS Code and create a new file

5. Save the file as `{filename}.ipynb`

6. Make sure you have activated the anaconda environment

7. Open the command palette and select `Jupyter: Create New Blank Jupyter Notebook`

8. Select the Python 3 kernel

9. Run the first cell

10. Add a new cell and run it
