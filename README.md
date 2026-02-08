# IS 362 – Jupyter Notebook Assignments

This repository contains Jupyter Notebook assignments for my IS 362 course.
All work is completed in Python using Jupyter Lab.

## Environment Setup (Windows)

### Install WSL (Windows Subsystem for Linux)

Open PowerShell as Administrator and run:

wsl --install

Restart your computer when prompted.

### Install Python, pip, and venv inside WSL

Open your WSL terminal and run:

sudo apt update
sudo apt install python3 python3-pip python3-venv -y

### Create and activate a virtual environment

From the project directory:

python3 -m venv venv
source venv/bin/activate

### Install Jupyter Lab

With the virtual environment activated:

pip install jupyterlab

## Starting Jupyter Lab

From the project directory, activate the virtual environment and run:

source venv/bin/activate
jupyter lab

Jupyter Lab will print a local URL in the terminal.
Open that link in your browser to access the notebooks.