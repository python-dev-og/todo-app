![Python 3.11](https://img.shields.io/badge/python-3.11-blue.svg)
![Streamlit 1.29.0](https://img.shields.io/badge/streamlit-1.29.0-orange.svg)
![PySimpleGUI 4.55.1](https://img.shields.io/badge/PySimpleGUI-4.55.1-green.svg)

# README.md for To-Do Application

## Overview
This repository contains a simple yet versatile To-Do application, providing both 
Command Line Interface (CLI) and Graphical User Interface (GUI) options, along with a Web application using Streamlit. 
The application allows users to manage their to-do lists effectively, with features like adding, showing, editing, completing, and removing tasks.

### Files Description:
1. `cli.py` - The command-line version of the To-Do app.
2. `functions.py` - Contains core functionalities used across the application, like reading and writing to-dos to a file.
3. `gui.py` - A GUI version of the To-Do app built with PySimpleGUI.
4. `web.py` - A web-based version using Streamlit.

## Installation and Running the Application

### Prerequisites:
- Python 3
- PySimpleGUI (for GUI version)
- Streamlit (for Web version)

### Setup:
1. Clone the repository to your local machine.
2. Install the necessary libraries:
   ```
   pip install PySimpleGUI streamlit
   ```

### Running the Application:
- For CLI:
  ```
  python cli.py
  ```
- For GUI:
  ```
  python gui.py
  ```
- For Web:
  ```
  streamlit run web.py
  ```

## Features

### CLI
- Add tasks with `add <task>`.
- Show all tasks with `show`.
- Edit tasks with `edit <task number>`.
- Complete tasks with `complete <task number>`.
- Exit the application with `exit`.

### GUI
- Add, edit, complete, and view tasks through a user-friendly interface.
- Real-time clock display.

### Web
- Simple Streamlit-based interface for task management.
- Add and complete tasks with interactive checkboxes.

## Contributing
Contributions to improve the application are welcome. Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Final Look 
###  CLI 
![cli.png](images%2Fcli.png)
### GUI 
![gui.png](images%2Fgui.png)
### Web Look
![web.png](images%2Fweb.png)

![web2.png](images%2Fweb2.png)