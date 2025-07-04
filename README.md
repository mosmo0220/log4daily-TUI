
### README.md

# log4daily-TUI
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg)](https://www.gnu.org/licenses/agpl-3.0)

## Project Overview 📖

**log4daily-TUI** is a work-in-progress application with the goal of providing a robust platform for task planning, milestone tracking, and journaling. 

**Please note:** This application is still under development, and the features outlined above are intended goals rather than completed functionalities.

### Installation 📥

To install **log4daily-TUI**, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/zaruuwa/log4daily.git
    cd log4daily
    ```

2. **Set the appropriate permissions:**

    For Linux and macOS:
    ```sh
    chmod +x install.sh
    ```

    For Windows:
    ```sh
    icacls install.sh /grant Everyone:F
    ```

3. **Run the installation script:**
    ```sh
    ./install.sh
    ```

This script will make binary file, copy it to app folder and add to console path

 ### Update 🔄
To update **log4daily-TUI** to the latest version, follow these steps:

1. **Navigate to the project directory:**
    ```sh
    cd log4daily
    ```

2. **Pull the latest changes from the repository:**
    ```sh
    git pull
    ```

3. **Run the installation script again:**
    ```sh
    ./install.sh
    ```

This will update your local copy of **log4daily-TUI** with the latest changes and ensure that everything is set up correctly.

### Project Structure 🗂️

📂 **app**: The main directory contain source files, include files and headers file

Documentation will be added at first stable version

### License 📜

This project is licensed under the **GNU Affero General Public License v3 (AGPL-3.0)**. For more information, refer to the [LICENSE](LICENSE) file.

### Used libraries 📦

- [**FTXUI**](https://github.com/ArthurSonzogni/FTXUI) for UI : License MIT
- [**l4dFiles**](https://github.com/mosmo0220/l4dFiles) for managing l4d files : License MIT

### Author 👤

Created by **Marcin Osmolak-Rogaluk**.
