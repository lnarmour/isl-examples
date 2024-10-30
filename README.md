# isl-examples

This repository contains several simple examples of the core functionality available in the integer set library (isl) exposed through the python bindings.

## Installation

Minimally, python3 is required. See [here](https://docs.python.org/3/using/unix.html) for installation instructions on linux.
On mac, you can use [homebrew](https://github.com/lnarmour/isl-examples), the macOS package manager, to install python:
```
brew install python3
```

### Set up a virtual environment

Create a new virtual environment, activate it, and install the necessary dependencies with the following commands:
```
python3 -mvenv virtual-islpy
source virtual-islpy/bin/activate
pip install -r requirements.txt
```

## Jupyter notebook

With the virtual environment activated as described above, launch the notebook app with the following command:
```
jupyter notebook
```

This should open a web page in your default browser with a view of the files in the current working directory.
From here you can create and interact with jupyter notebooks using the web GUI.
