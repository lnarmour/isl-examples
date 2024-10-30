# isl-examples

This repository contains several simple examples of the core functionality available in the integer set library (isl) exposed through the python bindings.

## installation

Minimally, python3 is required.
On linux, you can refer to the docs here:  
[https://docs.python.org/3/using/unix.html](https://docs.python.org/3/using/unix.html)

On mac, you can use "homebrew", the macOS package manager to install python3:
```
brew install python3
```

### set up a virtual environment

Create a new virtual environment with the following command:
```
python3 -mvenv virtual-islpy
```

Activate the environment:
```
source virtual-islpy/bin/activate
```

Install the dependencies (jupyter notebook, isl, etc):
```
pip install -r requirements.txt
```

## jupyter notebook

With the virtual environment activated as described above, launch the notebook app with the following command:
```
jupyter notebook
```

This should open a web page in your default browser with a view of the files in the current working directory.
From here you can create and interact with jupyter notebooks using the web GUI.
