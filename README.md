# MySQL-Frontend-GUI for Linux
A simple down-to-earth GUI frontend developed in Python3 for simple admin tasks on MySQL-Server running on the localhost. Developed for my CS School Project.

# What's different
This branch now has its GUI optimised for Linux systems using the fonts provided by MS.
Other than that, there's hardly any difference.

# System Requirements:
This program should run on your Linux computer with Python3, MySQL Server, and the below-mentioned Python Libraries installed in the virtual environment.

# Installation Pre-requisites
1. python3

2. pip 

3. Virtual Environment python3-venv package


4. MySQL/MariaDB-Server from v5.1 and above, active and running.

Use the installation guide below:
https://www.digitalocean.com/community/tutorials/how-to-install-mariadb-on-ubuntu-20-04

# Installation and Running

1. Download the entire repo contents as a .zip and extract it in a folder on your computer.

2. Users are required to run a virtual environment on your own, so kindly follow the below given steps:

Step 1:
Open the folder in terminal.
Step 2:
Navigate to your project directory.
Step 3:
Run the command to create a new virtual environment.
```bash
cd /path/to/your/project
python3 -m venv venv
```
Step 4:
Activate the virtual environment.
On Debian/Ubuntu systems, you need to install the python3-venv
package using the following command.
```bash
 apt install python3.10-venv
```
You may need to use sudo with that command.  After installing the python3-venv
package, recreate your virtual environment.

3. Ensure that MariaDB is running with the systemctl start command:
```bash
sudo systemctl start mariadb.service
```
4. Execute the python file MySQL-Frontend_v2.0XX.py on your Python shell.

5. Installation complete!

