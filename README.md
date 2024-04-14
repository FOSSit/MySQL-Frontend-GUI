# MySQL-Frontend-GUI for Linux

MySQL-Frontend-GUI for Linux is a simple yet effective graphical user interface developed in Python3 for performing basic administrative tasks on a MySQL Server running on localhost. Originally developed for a CS school project, this GUI provides an intuitive interface for managing MySQL databases.

## What's Different

This branch of the project has optimized the GUI specifically for Linux systems, utilizing fonts provided by Microsoft. While there are minimal differences compared to previous versions, this enhancement ensures a better user experience on Linux platforms.

## System Requirements

To run this program on your Linux computer, you'll need the following prerequisites:

- Python3
- MySQL Server
- Python libraries listed below, installed within a virtual environment:

## Installation Pre-requisites

Before running the program, ensure you have the required Python libraries installed in the virtual environment. These libraries are included in the project's (.venv) virtual environment:

1. `pyqt5`
2. `pyqt5-tools`
3. `mysql-connector`

Additionally, you'll need MySQL/MariaDB-Server version 5.1 or above installed and running on your system.

## Installation and Running

Follow these steps to install and run MySQL-Frontend-GUI:

1. **Download Repository**: Download the entire repository contents as a .zip file and extract it into a folder on your computer.

2. **Activate Virtual Environment**: Navigate to the `.venv` directory and activate the virtual environment by running the appropriate shell script found in `./.venv/bin/<activate_shell_script>`.

3. **Run the Program**: Execute the Python file `MySQL-Frontend_v2.0XX.py` in your Python shell.

   ```bash
   python MySQL-Frontend_v2.0XX.py

Execution via Executable: Alternatively, you can directly execute the MySQL Frontend Executable using the soft link file provided in the repository.

You're Done!: Once the program is running, you can start using MySQL-Frontend-GUI to perform various administrative tasks on your MySQL Server.

This GUI simplifies database management tasks on Linux systems, offering an accessible and user-friendly interface. Feel free to explore its features and functionalities to streamline your MySQL database administration.

If you encounter any issues or have feedback, please don't hesitate to reach out. Happy database administration!

You can save this content in a file named README.md in your project repository. Let me know if you need further assistance!
