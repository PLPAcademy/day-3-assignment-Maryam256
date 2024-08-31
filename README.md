[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vnsr1XuU)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15656884&assignment_repo_type=AssignmentRepo)
# Env_Set

# Environment Setup Assignment

#Dart & Flutter

1. What is the first step for installing Dart on a Windows machine?
2. Go to the Dart website: Open your web browser and navigate to the Dart SDK download page.
Select the Windows option: Scroll down to find the Windows section.
Download the Dart SDK: Click on the "Download Dart SDK" link to download the .zip file.
2. Extract the Dart SDK
Locate the downloaded file: Go to the folder where the Dart SDK .zip file was downloaded.
Extract the contents: Right-click on the .zip file and select "Extract All..." Choose a directory where you want to extract the Dart SDK.
3. Add Dart to the System PATH
Open System Properties:
Press Windows + X and select "System".
Click on "Advanced system settings" on the left side.
Access Environment Variables:
In the System Properties window, click on the "Environment Variables" button.
Edit the PATH Variable:
In the "System variables" section, find and select the "Path" variable, then click "Edit".
Add Dart SDK Path:
Click "New" and enter the path to the bin directory inside the Dart SDK folder you extracted. For example: C:\path\to\dart-sdk\bin.
Save Changes:
Click "OK" to save changes in all open windows.
4. Verify the Installation
Open Command Prompt:
Press Windows + R, type cmd, and press Enter.
Check Dart Version:
Type dart --version and press Enter. If Dart is installed correctly, it will display the version of Dart you installed.

A) Install Homebrew
Open Terminal
Press Cmd + Space to open Spotlight Search, type "Terminal," and press Enter.
2. Install Xcode Command Line Tools (macOS only)
Before installing a home brew on macOS, you need to install the Xcode Command Line Tools.
In Terminal, type the following command and press Enter:
After installation, you may need to add Homebrew to your PATH to ensure you can use it from the terminal. The installation script usually suggests the command you need to add to your shell configuration file.
To confirm that Homebrew is installed correctly, type the following command and press Enter

B) Download the Dart SDK
 Visit the Official Dart Website
Open your web browser and go to the Dart SDK download page.
 Choose the Windows Option
On the download page, scroll down until you see the section for Windows.
You'll find options to download the Dart SDK.
  Download the Dart SDK
Click the "Download Dart SDK" link. This will download a .zip file containing the Dart SDK.
 Extract the SDK
Once the download is complete, locate the .zip file in your Downloads folder or wherever you saved it.
Right-click on the file and choose "Extract All..." to unzip the SDK.

C) Update your PATH

To update your PATH on a Windows machine so that Dart commands are recognized system-wide, follow these steps:

1. Locate the Dart SDK bin Directory
After downloading and extracting the Dart SDK, locate the folder where you extracted it.
Inside the extracted folder, find the bin directory (e.g., C:\path\to\dart-sdk\bin).
2. Open System Properties
Press Windows + X and select "System" from the menu.
In the System window, click on "Advanced system settings" on the left-hand side.
In the System Properties window, click on the "Environment Variables" button.
3. Edit the PATH Variable
In the Environment Variables window, find and select the "Path" variable under the "System variables" section, then click "Edit..."
In the Edit Environment Variable window, click "New" and add the path to the bin directory of the Dart SDK (e.g., C:\path\to\dart-sdk\bin).
4. Save the Changes
Click "OK" to close the Edit Environment Variable window.
Click "OK" again to close the Environment Variables window.
Click "OK" to close the System Properties window.
5. Verify the PATH Update
Open Command Prompt by pressing Windows + R, typing cmd, and pressing Enter.
Type dart --version and press Enter.
If the PATH is updated correctly, you should see the Dart SDK version information displayed.

D) Run Dart Doctor
Open Command Prompt
Press Windows + R, type cmd, and press Enter to open the Command Prompt.
2. Run dart doctor
In the Command Prompt, type the following command and press Enter.
The dart doctor command will check your Dart environment and list any issues that need to be addressed. This might include checking for the Dart SDK installation, verifying the PATH, and identifying any missing



2. Which command verifies the Dart installation on macOS?

A) dart --install
B) dart --check
C) dart --verify
D) dart --version

D) dart --version


3. What is the next step after downloading and extracting the Flutter SDK on Linux?

A) Install Homebrew
B) Update your PATH
C) Run Flutter Doctor
D) Create a new Flutter project

B) Update your PATH


4. What command is used to run a newly created Flutter app?

A) flutter start
B) flutter build
C) flutter run
D) flutter init

C) flutter run


#Python Installation

What is the first step to install Python on a Windows system?

A) Run the installer without any customization
B) Download Python from the official website
C) Open the terminal and type sudo apt install python
D) Install pip manually

B) Download Python from the official website.

Which option should you ensure is checked during Python installation on Windows?

A) Install with default settings
B) Install to a custom directory
C) Add Python to PATH
D) Install all available features

C) Add Python to PATH

How do you verify Python installation on any system?

A) By running python --version
B) By restarting your computer
C) By opening the Python installer again
D) By checking the Programs and Features in Control Panel

A) By running python --version

What command is used to install pip on macOS and Linux?

A) sudo install pip
B) pip install python
C) curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
D) python --install pip

C) curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

What is the purpose of a virtual environment in Python?

A) To keep your projects organized in one folder
B) To install Python in a different directory
C) To separate project dependencies and avoid conflicts
D) To enhance Python performance on your system

C) To separate project dependencies and avoid conflicts

#MySQL Installation

What is the first step to install MySQL on Windows?

A) Download MySQL Shell
B) Download MySQL Installer from the official website
C) Install MySQL Workbench
D) Set up a root password

B) Download MySQL Installer from the official website

What setup type should you choose for a custom MySQL installation?

A) Developer Default
B) Server Only
C) Full
D) Custom

D) Custom

Which products should you select during the MySQL installation?

A) MySQL Server, MySQL Workbench, and MySQL Shell
B) Only MySQL Server
C) MySQL Server and MySQL Router
D) MySQL Workbench and MySQL Utilities

A) MySQL Server, MySQL Workbench, and MySQL Shell

What is the purpose of setting a root password during MySQL installation?

A) To create a user account for your MySQL server
B) To secure your MySQL installation with a super-secret password
C) To activate MySQL Workbench
D) To allow multiple users to access MySQL

B) To secure your MySQL installation with a super-secret password

How do you begin managing your database after installing MySQL?

A) Start by installing additional plugins
B) Launch MySQL Workbench and connect to your MySQL Server
C) Run mysqladmin start in the terminal
D) Restart your computer to activate MySQL

B) Launch MySQL Workbench and connect to your MySQL Server
