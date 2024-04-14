# MySQL Frontend GUI

The MySQL Frontend GUI is a graphical user interface designed to interact with MySQL databases efficiently. It provides users with a convenient way to manage databases, execute queries, and visualize data.

## Project Overview

The MySQL Frontend GUI aims to streamline database management tasks for developers and database administrators. Key features include:

- Database Connection: Easily connect to MySQL databases using credentials.
- Query Execution: Execute SQL queries and view results in a user-friendly interface.
- Data Visualization: Visualize database schemas, tables, and query results for better insights.

### Key Technologies

The MySQL Frontend GUI is built using the following key technologies:

- Python programming language
- PyQt5 for the graphical user interface
- MySQL Connector/Python for database connectivity

## Installation Guide

### System Requirements

- Python 3.x
- PyQt5 library
- MySQL Connector/Python library

### Cloning the Repository

```bash
git clone https://github.com/FOSSit/MySQL-Frontend-GUI.git
cd MySQL-Frontend-GUI
```
# Installing Dependencies
Install dependencies using pip:
        pip install -r requirements.txt
# Usage
Run the application:
    python main.py

# MariaDB Setup Guidance
## Linux
Install MariaDB server:
    sudo apt update
    sudo apt install mariadb-server
Secure MariaDB installation:
    sudo mysql_secure_installation
Start and enable MariaDB service:
    sudo systemctl start mariadb
    sudo systemctl enable mariadb
Access MariaDB shell:
    sudo mysql -u root -p
Create a database and user:
    CREATE DATABASE mydatabase;
    CREATE USER 'myuser'@'localhost' IDENTIFIED BY 'mypassword';
    GRANT ALL PRIVILEGES ON mydatabase.* TO 'myuser'@'localhost';
    FLUSH PRIVILEGES;
Windows
Download MariaDB installer from the official website: MariaDB Downloads.

Follow the installer instructions to complete the installation process.

Start MariaDB service from the Services application or using the command line.

Access MariaDB command-line client from the Start menu or using the command prompt.

Follow the same steps as Linux to create a database and user.

Contributing
Contributions to the MySQL Frontend GUI project are welcome! To contribute, please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.




