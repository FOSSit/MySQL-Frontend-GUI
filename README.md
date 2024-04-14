# MySQL-Frontend-GUI for Linux

A simple down-to-earth GUI frontend developed in Python3 for simple admin tasks on MySQL-Server running on the localhost. Developed for my CS School Project.

## What's different

This branch now has its GUI optimised for Linux systems using the fonts provided by MS.
Other than that, there's hardly any difference.

## System Requirements

This program should run on your Linux computer with Python3, MySQL Server, and the below-mentioned Python Libraries installed in the virtual environment.

## Installation pre-requisites

1. The Following Python Libraries are required to execute the program:
    - `pyqt5`
    - `pyqt5-tools`
    - `mysql-connector`
    \
    These libraries are available in the project's (.venv) virtual environment.

2. MySQL/MariaDB-Server with v5.1 and above, active and running.

## Installation and Running

1. Download the entire repo contents as a `.zip` and extract it in a folder on your computer, or you can also clone the repository URL by running the command `git clone <repository-url>`.
2. Enable the venv by running the appropriate shell script fount in `./.venv/bin/<activate_shell_script>`
3. Execute the python file `MySQL-Frontend_v2.0XX.py` on your Python shell.
4. You are done.
5. Or just execute the MySQL Frontend Executable using the soft link file in the repo.

## Quick guide on the credentials

The credentials used to login are:

Username: `root`

Password: `<the password set by you on installation>`
