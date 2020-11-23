# Jupyter + Virtual Environments

### 👨🏻‍💻Hacking together a quick shell script to get them to work together

It's annoying to install and set up Jupyter Lab properly each time you create a virtual environment, so I wrote a short shell script that installs the relevant packages, some useful extensions, and most importantly registers the venv as a kernel to make it available in Jupyter.

## 🔌Installation

Create a virtual environment for your project and navigate to the parent directory.

- Activate your virtual environment

- Make sure you're in the root folder and run:

    ```bash
    git clone https://github.com/adcoh/jupyterlab-helper.git jupyterlab_helper && cp jupyterlab_helper/jupyterlab_venv_installer.sh jupyterlab_venv_installer.sh && rm -rf jupyterlab_helper
    jupyterlab_venv_installer.sh
    ```

This will do the following

1. Clone the shell script into your project, copying it to your root directory, then deleting the repo
2. Installs [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) & autopep8 (because nicely formatted Python is always good)
3. Makes the virtual environment available as a Jupyter kernel
4. Enable and install Jupyter Lab extensions
5. Reloads Jupyter Lab

## 💥Start Jupyter Lab

To start Jupyter Lab, type the following in the terminal: 

```bash
jupyter lab
```

A browser window will open with our Jupyter Server running.

Hope you find this useful ☮️
