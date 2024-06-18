[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15284346&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

Setting up my developer environment ANSWERS:
1)	Download an Operating System like Windows 11
https://www.microsoft.com/software-download/windows11 

2)	Create GitHub Account
•	Go to https://github.com/ and sign up for account
•	Verify your email address
•	Set up your profile

3)	Download Git
Step 1: 
•	Open your favorite web browser and navigate to https://www.git-scm.com/download/win , to download git for windows.
•	Select “click here to download” the latest version of Git for Windows, however, to make sure whether your computer is 32-bit or 64-bit and download accordingly. 
•	Save the installer in your computer

Step 2: Run the Installer
•	Double click on the download git installer file
•	Follow the prompts to install git and adjust according to your needs but make sure that you select the option to add Git to your PATH environment
•	After following all prompts, finally click install to complete the installation process

Step 3: Launch Git Bash
•	Open the start menu and search for Git Bash
•	Launch Git bash. When opening its advisable to run as administrator.

Step 4: Configure your Git Settings
•	Run the command: git config - -global user.name “YourGitHubName”
•	Run the command: git config - -global user.email YourGitHubemail@gmail.com


Step 5: Verify your Git Installation
•	Run the command: git - -version
•	You should see the version of Git installed

Now that you’ve configured your Git settings

Step 6: Create a new local repository (to create inside Git Bash)
•	To navigate to where you would like your folder to be created run command: cd <C:/ , Downloads, Documents, Desktop> anywhere on your computer
•	To create a directory run command: mkdir <dir_name> , (replace <dir_name> with the name of your folder/directory)
•	Run command: cd <dir_name> to Navigate to the directory
•	Run command: git init , to initialize a new Git repository

Step 7: Add files or changes to your local repository
•	Add files under your folder you created(in file explorer or text editors like VS Code)
•	Make any changes you need to make if there’s any
•	Run command: `git add .` to stage all files and changes made
•	Run command: `git commit -m “message of changes made”’`

Step 8: Link the local repository to GitHub
•	Create a new GitHub remote repository
•	Copy the Repository URL
•	Go back to Git Bash and Run command: `git remote add origin <Ctrl+V GitHub repository URL>`
•	Run command:`git remote -v` to verify the connection

Step 9: Push the changes to GitHub
•	Run command: `git push -u origin main`(or the branch you want to push to). 
•	Enter GitHub login information or credentials when prompted.



4)	Download VS Code
•	Open web browser of your choice and navigate to https://code.visualstudio.com/ 
•	Click on the Download button
•	Run the installer
•	Follow prompts
•	Launch VS Code
•	Install Extensions

5)	Install Extensions in VS Code
•	Python
•	Prettier
•	Pylance
•	Python Debugger
•	Python image preview
•	Code Runner
•	Path Intellisence
•	Flutter
•	Dart

6)	Download Python for Windows
•	Go to https://www.python.org/ in your browser
•	Hover the downloads button
•	Select the python latest version appearing under “Download for windows”
•	Download the installer
•	Run the downloaded installer
•	Follow the installation prompts
•	Add Python to your PATH environment
•	Verify the installation: Open a terminal like powershell or command prompt and type: python - - version to verify the successful installation of Python.

7)	Download python package manager pip(Python Package Installer)
•	Pip comes with Installation of Python added to PATH
•	However there is an alternative for older Python versions
•	Open a terminal or command prompt
•	Type python -m ensurepip to install pip
•	Then press enter  to execute command and install pip
•	Once installed, verify by running: pip - -version 
•	This will then display the version of pip installed

8)	Adding Installations to PATH in the environment variables
•	Open start menu and search for environment variables 
•	`Edit the system environment variables` control panal
•	Click on environment variables
•	Double on PATH under local system
•	Add new PATH
•	Paste the PATH of that particular installation

9)	Download mySQL
•	Go to https://dev.mysql.com/downloads/installer/ 
•	Download the second installation
•	Choose where to save installation
•	Run the installation
•	Follow the installation prompts
•	Finish installation
•	Copy PATH and add to environment variables

10)	Download Flutter SDK
•	Go to https://docs.flutter.dev/get-started/install/windows/desktop?tab=download#install-the-flutter-sdk 
•	Under “Install the Flutter SDK” , select the option Download and Install in that column
•	Than select on the Flutter-windows_3.22.2-stable.zip to download
•	Extract the zip file
•	Add to PATH environment variables 

11)	Download Dart
•	Go to https://dart.dev/get-dart/archive#stable-channel 
•	Select stable channel option at the right panel options of your screen
•	Under stable channel, download the Dart SDK (SHA-256)
•	Choose where to store it in your pc
•	Extract the zip file
•	Add to PATH environment variables 

12)	Python Project with Django Step-by-Step process
•	cd Downloads
•	mkdir dir_name
•	cd dir_name
•	python - - version
•	pip - -version
•	Install virtual environment (if not installed):
•	python -m pip install virtualenv
•	To create virtualenv
•	Python -m virtualenv <envname>
•	Activate your virtualenv, run command: 
•	source envname/Scripts/activate
•	Install Django(You install in all your projects):
•	python -m pip install Django
•	Verify installations:
•	python -m Django - -version
•	django -admin - - version
•	Now START PROJECT:
•	django -admin startproject <projectname>
•	cd projectname/
•	ls
•	START APP inside project folder:
•	django-admin startapp <appname>
•	ls
•	code . 
•	VS Code opens

NOW ON VS CODE
Now that VS Code is open, you will find your project folder. Within it you will find your project folder created by Django and your App folder. To Distinguish these two folders, the app folder has apps.py and views.py files in it, and the project folder has settings.py files within it. 
First things first, is to open your apps.py file and copy the name of your app.
Navigate to settings.py and once in the file, scroll down, and under INSTALLED APPS, paste the app name at the end of the code, following the procedure and syntax there.
Now go back to your project in Git Bash, and run the command: python manage.py runserver and then ctrl+c to stop the server running. 
Copy the http link with the port number. 
Again, run command: python manage.py runserver…do not stop the server now
Go to your favorite web browser, and paste the http url there. 
Django app, should display running. 
This is as far I have gone with the project.

GITHUB repository containing a sample project:
My first Ecommerce project with Django: https://github.com/sphumelelezuma/Ecommerce-App.git 


Reflection on the challenges faced
Had challenges with adding my remote repository using the command `git remote add origin https://github.com/sphumelelezuma/Ecommerce-App.git `, it encountered an error. 
However after prompting AI carefully, I realized that because now I have decided to create a new Repository to link with my local repo, the old repo was the origin, so I had to set this url https://github.com/sphumelelezuma/Ecommerce-App.git as the origin instead. 
So I then commanded: `git remote set-url origin https://github.com/sphumelelezuma/Ecommerce-App.git ` 



#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
