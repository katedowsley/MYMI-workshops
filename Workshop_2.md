# Workshop 2: Using Python to Create a Healthcare Application


# Table of Contents
1. [Introduction](#Introduction)

2. [Setup](#Setup)
    
    2.1. [Install Required Software](#Install-Required-Software)
    
    2.2. [Create a Virtual Environment](#Create-a-Virtual-Environment)

3. [Key Concepts + Basic Examples](#Key-Concepts-+-Basic-Examples)

4. [Ideation](#Ideation)

5. [Backend Code](#Backend-Code)

6. [GUI - Frontend Code](#GUI---Frontend-Code)

7. [Integrate GUI with Backend](#Integrate-GUI-with-Backend)

8. [Export as Standalone Application](#Export-as-Standalone-Application)

## Introduction

## Setup
If you run into any issues before the workshop email info@mymi.org.au and put "Workshop 2 Setup" in the subject line. If you are still having trouble, demonstrators can help you on the day!

### Install Required Software
If you run into any issues, consult the [reference documentation](https://code.visualstudio.com/docs/python/python-tutorial)

1. Download VS Code from [here](https://code.visualstudio.com/download)

2. Install the Python Extension in VS Code from the Extensions Marketplace tab as shown below

<img width="393" alt="image" src="https://user-images.githubusercontent.com/101687676/158518484-994f8d23-fbd1-47f0-8877-b3de44007840.png">
  
3. Install a Python Interpreter

**Windows:** Install from here https://www.python.org/downloads/

**Mac:** Open terminal 

<img width="673" alt="image" src="https://user-images.githubusercontent.com/101687676/158518753-a9cbae6a-6e6b-474e-b815-b3157422d137.png">
    
Install homebrew by typing the following line in terminal: ```/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"```
    
Note: you may be asked to type your password.
    
Install the latest Python Interpreter by typing the following line terminal: ```brew install python```  
&nbsp;

### Create a Virtual Environment

Why? Virtual environments keep things tidy! It creates an isolated environment for your project so that you don't run into issues with using different versions of Python libraries in future projects. It's good practice to create a new virtual environment for each new Python project.

Read more about virtual environments [here](https://docs.python.org/3/library/venv.html)

1. Create a folder on your computer and call it "MYMI_Workshop_2"

2. Open a command line program and install the package for creating virtual envrionments. This might take a few minutes

**Windows:** Open Command Prompt or Powershell

**Mac:** Open Terminal

```pip install venv```

3. In Terminal/Command Prompt/Powershell, navigate to the folder that you created using the command ```cd /path_to_folder/MYMI_Workshop_2``` 

See the example below using Terminal where the MYMI_Workshop_2 folder is saved on the desktop:
<img width="391" alt="image" src="https://user-images.githubusercontent.com/101687676/158522102-42942dfd-a5f7-4fe4-8ae6-a46b6c6e56eb.png">

Helpful command line commands:
- view the folders in your current directory using ```ls``` (Terminal and Powershell) or ```dir``` (Command Prompt)
- type ```cd``` followed by the folder name to move into a folder
- hit tab to autocomplete file and folder names


4. Type ```python3 -m venv ./venv``` and hit enter to create the virtual environment. This should take less than 2 minutes.

&nbsp;

5. Activate the virtual environment 

Fix windows stuff!!!

**Powershell (Windows):** ```Scripts\Activate.ps1```

**Command Prompt (Windows):** ```Scripts\activate.bat```

**Terminal (Mac):** ```source venv/bin/activate```

If you want to exit the virtual environment simply type ```deactivate```

&nbsp;

6. Check that Python is working in the virtual environment
- make sure that the virtual environment is activated. The terminal line should now have (MYMI_Workshop_2) at the start of the line as shown below
<img width="434" alt="image" src="https://user-images.githubusercontent.com/101687676/158524038-4099eae6-d252-4efe-a7b7-5f683376e70c.png">

- Type ```python``` then hit enter. Ther version number should be at least 3.8
- Type ```exit()``` and hit enter
<img width="515" alt="image" src="https://user-images.githubusercontent.com/101687676/158524115-513783b1-b1af-4f7e-aeb1-24168bfed261.png">


7. Install the required packages

Download the [requirements.txt](./requirements.txt) file and save it in the "MYMI_Workshop_2" folder

Type ```pip install -m requirements.txt``` in your command line program.

This should take sdkfjlasjdf minutes

### Check your setup
1. Open the folder in VS Code and select interpreter as the virtual environment. In mac shift, command, P --> select interpreter:

<img width="596" alt="image" src="https://user-images.githubusercontent.com/101687676/160950580-e0abf162-2b03-4e10-9982-1fb209dc5c66.png">

3. Click 

## Key Concepts + Basic Examples

## Ideation

## Backend Code

## GUI - Frontend Code

## Integrate GUI with Backend

## Export as Standalone Application
