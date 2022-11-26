# Pyenv for Windows
Quick guide to install pyenv on Windows PowerShell

## Introduction

As a developer, you need agility in changing between python versions. Here we come with an excellent option. Pyenv is a command line tool that enables you to switch from one version to another, install specific packages for each version or execute a particular python script that only runs with a previous version than yours.

## Instalation

1. Open your PowerShell terminal
2. Execute this command:
    ```bash
    Invoke-WebRequest -UseBasicParsing -Uri "https://raw.githubusercontent.com/pyenv-win/pyenv-win/master/pyenv-win/install-pyenv-win.ps1" -OutFile "./install-pyenv-win.ps1"; &"./install-pyenv-win.ps1"
    ```

    You can see something like this image:

    ![INSTALLATION](images/installation.png)

3. Close and reopen your terminal before using it.