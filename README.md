# Meta-Learning Project

This repository contains code and dependencies for running experiments
in Jupyter Notebook. Follow the steps below to set up and run the
project.

------------------------------------------------------------------------

## 🚀 Setup Instructions

### 1. Create a Virtual Environment (Windows)

Open **Command Prompt** or **PowerShell** in the project folder and run:

``` bash
python -m venv env
```

Activate the virtual environment:

``` bash
env\Scripts\activate
```

------------------------------------------------------------------------

### 2. Install Dependencies

Once the environment is activated, install all required packages:

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

### 3. Create a Jupyter Kernel

To use the virtual environment inside Jupyter Notebook:

``` bash
pip install ipykernel
python -m ipykernel install --user --name=env --display-name "Python (env)"
```

Now, when you open Jupyter Notebook, you'll be able to select **Python
(env)** as the kernel.

------------------------------------------------------------------------

### 4. Run the Notebook

Launch Jupyter Notebook:

``` bash
jupyter notebook
```

Open `whatever.ipynb` and run the cells **block by block** to execute
the code.

----------------------------------------------------------------------
