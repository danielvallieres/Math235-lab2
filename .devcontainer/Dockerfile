
# Indicate which dev container to use.  The current one cannot be started with Jupyter Lab.
FROM mcr.microsoft.com/devcontainers/python:1-3.11-bullseye


# Install SageMath.  One needs the -y option to answer yes for the installation process to carry on.
# We also need to install jupyterlab to be able to open the codespace with this editor rather than vscode. 
RUN sudo apt update && sudo apt install -y sagemath && pip3 install jupyterlab
