
# MySQL-Frontend-GUI for Linux

MySQL-Frontend-GUI is a Python3-based graphical user interface (GUI) frontend designed for performing basic administration tasks on a MySQL or MariaDB server running on localhost. This project was developed as a CS school project and provides a simple yet effective tool for database management.

## Project Overview

The MySQL-Frontend-GUI utilizes the following key technologies:

- **Python3**: Programming language used for the backend functionality.
- **PyQt5**: Python bindings for the Qt application framework, used for GUI development.
- **MySQL Connector**: Python library to connect and interact with MySQL/MariaDB databases.

## System Requirements

Before running the application, ensure you have the following installed:

- Python 3.x
- MySQL Server (version 5.1 and above) or MariaDB Server
- Required Python libraries (`pyqt5`, `pyqt5-tools`, `mysql-connector`)

## Installation

### Clone the Repository

```bash
git clone <https://github.com/FOSSit/MySQL-Frontend-GUI>
cd MySQL-Frontend-GUI

## Setup Virtual Environment (optional but recommended)

```bash
python3 -m venv .venv
source .venv/bin/activate

## Install Dependencies
```bash
pip install -r requirements.txt

Ensure you have activated your virtual environment before running the above command if you're using one.

# MariaDB Setup

## Linux

### Install MariaDB Server:

```bash
sudo apt update
sudo apt install mariadb-server

### Start MariaDB service and secure installation:

```bash
sudo systemctl start mariadb
sudo mysql_secure_installation

# Windows
Download and install MariaDB from the official website: [MariaDB Downloads](https://mariadb.org/download/?t=mariadb&p=mariadb&r=11.3.2&os=windows&cpu=x86_64&pkg=msi&mirror=aliyun)

# Running the Application

## Activate Virtual Environment (if used):

```bash
source .venv/bin/activate

## Run the Python Script:
```bash
python MySQL-Frontend_v2.0XX.py

Replace MySQL-Frontend_v2.0XX.py with the appropriate filename. Alternatively, run the executableprovided.


# Usage

Upon running the application, you will be presented with a GUI interface to connect to your MySQL/MariaDB Server. Enter the required credentials (such as hostname, username, password), and you'll be able to perform database management tasks through the graphical interface.

# Contributing

Contributions to this project are welcome! If you have any suggestions, enhancements, or bug fixes, please feel free to open an issue or submit a pull request.

#License
This project is licensed under the [MIT License](https://opensource.org/license/MIT).