# Shell Script For Installing Jupyter Lab in Virtual Environment

It's annoying to install and set up Jupyter Lab properly each time you create a virtual environment, so I wrote a short shell script that installs the relevant packages, some useful extensions, and most importantly registers the venv as a kernel to make it available in Jupyter.

## Installation
 1. Clone this repo to your local machine
 2. Copy the jupyterlab_install.sh file to the directory that holds your venv directory
 3. Activate your venv
 4. Run the script in the terminal
 5. Start Jupyter Lab as usual, your venv should be available as a kernel with the same name as your venv directory
