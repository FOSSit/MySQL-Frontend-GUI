# MySQL-Frontend-GUI for Linux

MySQL-Frontend-GUI is a simple graphical user interface (GUI) frontend developed in Python3 for performing basic administrative tasks on a MySQL Server running on localhost. Originally developed for a CS school project, this GUI is now optimized for Linux systems using fonts provided by Microsoft.

## What's Different

This branch of the project has its GUI optimized for Linux systems, ensuring compatibility with the fonts available on those systems. Other than this optimization, there are hardly any differences from the original version.

## System Requirements

To run this program on your Linux computer, ensure that you have the following prerequisites:

- Python 3 installed on your system
- MySQL Server installed and running (version 5.1 and above)
- Python libraries installed in a virtual environment:
  - `pyqt5`
  - `pyqt5-tools`
  - `mysql-connector`

These libraries are available in the project's virtual environment (`.venv`).

## Installation Pre-requisites

1. Ensure that the required Python libraries mentioned above are installed in the virtual environment.

2. Make sure MySQL/MariaDB-Server version 5.1 and above is active and running on your system.

## Installation and Running

Follow these steps to install and run the MySQL-Frontend-GUI:

1. Download the entire repository contents as a .zip file and extract it into a folder on your computer.

2. Activate the virtual environment by running the appropriate shell script found in `./.venv/bin/<activate_shell_script>`.

3. Execute the Python file `MySQL-Frontend_v2.0XX.py` on your Python shell.

4. You're done! The MySQL Frontend GUI should now be running.

Alternatively, you can directly execute the MySQL Frontend Executable using the soft link file provided in the repository.

With these installation instructions, you should be able to set up and run the MySQL-Frontend-GUI on your Linux system seamlessly. Enjoy using the GUI for your MySQL administration tasks!
