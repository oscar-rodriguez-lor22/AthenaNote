# AthenaNote: A Simple Text Editor

AthenaNote is a lightweight, Python-based text editor built using Tkinter. It is designed to help you manage and edit plain text (.txt) files within specific folders on your local machine.
## Features
- Create Folders: Organize your notes by creating new directories.
  
- Open Existing Folders: Navigate to and open any folder containing .txt files.
  
- List Files: Once a folder is opened, all .txt files within it are displayed as clickable buttons on the left panel.

- Open and Edit Files: Click on a file to load its content into the main text area for editing.

- Save Files: Save changes to the currently open file.

- Create New Files: Add new .txt files to the currently open folder.

- Basic Name Validation: Prevents the use of invalid characters in folder and file names.

## Requirements

To run AthenaNote, you need:

Python3 : </br>
The application is written in Python.

Tkinter: </br>
This is Python's standard GUI library and is usually included with most Python installations.

## How to Run
Save the code: </br>
Save the provided Python code into a file named athenanote.py (or any .py extension you prefer).

Open a terminal or command prompt: </br>
Navigate to the directory where you saved the file.

Run the script: </br>
Execute the following command:

```
python athenanote.py
```

This will launch the AthenaNote application window.

## Usage

### Main Menu:

"Create Folder": </br>
Click this to select a location where you want to create a new folder for your text files. You'll then be prompted to enter a name for the new folder. After creation, the app will automatically switch to the Text Editor view, displaying the new folder's contents (initially empty).

"Open Folder": </br>
Click this to select an existing folder on your system. Once opened, the app will switch to the Text Editor view, listing all .txt files found in that folder on the left panel.

### Text Editor View:
File List (Left Panel): </br>
This panel will show buttons for each .txt file in your currently opened folder.

Open a File: </br>
Click on any file button in the left panel to load its content into the main text area for viewing and editing.

Edit Content: </br>
Type directly into the large text area to modify the file's content.

"Save" Button: </br>
Click this button to save any changes you've made to the currently open file.

"New File" Button: </br>
Click this to create a new .txt file in the current folder. You'll be prompted to enter a name for the new file. It will then appear in the file list.
