# AirBnB Clone v2 - ALX Project

Welcome to the **AirBnB Clone v2** project repository. This project is part of the ALX Software Engineering curriculum and is an upgrade of the previous version. The goal is to deploy on a server web static and create a distribution script. This version introduces more advanced features, including database storage, web framework integration, and enhanced deployment scripts.

## Table of Contents

1. [Project Overview](#project-overview)
2. [File Structure](#file-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Contributors](#contributors)
6. [License](#license)

## Project Overview

The **AirBnB Clone v2** project is designed to develop a clone of the AirBnB web application. The project is divided into several stages, each focusing on different aspects of the web application, such as storage, front-end integration, and deployment.

## File Structure

The repository contains the following files and directories:

- **0-setup_web_static.sh**: A Bash script that sets up your web servers for deployment of `web_static`.
- **1-pack_web_static.py**: A script that generates a .tgz archive from the contents of the `web_static` folder.
- **100-clean_web_static.py**: A script that deletes out-of-date archives.
- **101-setup_web_static.pp**: A Puppet manifest that sets up your web servers for deployment of `web_static`.
- **2-do_deploy_web_static.py**: A script that distributes an archive to your web servers.
- **3-deploy_web_static.py**: A script that creates and distributes an archive to your web servers.
- **7-dump.sql**: SQL script that generates a MySQL database dump.
- **AUTHORS**: A file that lists all individuals who have contributed to this repository.
- **console.py**: The command interpreter for the AirBnB clone.
- **models/**: Directory containing all the models used in this project.
- **setup_mysql_dev.sql**: SQL script to set up a MySQL database for development.
- **setup_mysql_test.sql**: SQL script to set up a MySQL database for testing.
- **tests/**: Directory containing all the unit tests for this project.
- **web_flask/**: Directory containing the web framework used for this project.
- **web_static/**: Directory containing static HTML files.

## Installation

To install and run this project, follow these steps:

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/your_username/AirBnB_clone_v2.git
    cd AirBnB_clone_v2
    ```

2. Set up your environment and install dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Set up the MySQL databases:
    ```sh
    cat setup_mysql_dev.sql | mysql -uroot -p
    cat setup_mysql_test.sql | mysql -uroot -p
    ```

4. Run the web server:
    ```sh
    ./0-setup_web_static.sh
    ```

## Usage

You can interact with the project using the command interpreter `console.py`:
```sh
./console.py

## Contributors

The following contributors have significantly contributed to the HBNB project in this repository:

Khalid Elaasry - khalidelassry22@gmail.com
ELMbadr - @gmail.com
