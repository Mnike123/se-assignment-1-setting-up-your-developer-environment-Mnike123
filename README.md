[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15247659&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

•	The first step is to check for updates, by going to Settings and then check for updates and secure.
•	Then download and install Windows 11.
•	Agree to the terms with “Agree and install” button.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
   •	To install Visual Studio Code on Windows, use the following winget command: winget install -e --id Microsoft.VisualStudioCode
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
To install Git on Windows here are the following steps:
•	Download the latest Git for Windows installer from the official Git website: https://git-scm.com/downloads
•	Run the installer and follow the prompts, accepting the default options. Make sure to include Git Bash and Git GUI during the installation.
•	Open a Command Prompt or Git Bash and run the following commands to configure your Git username and email:
(a)	git config --global user.name "Your Name"
(b)	git config --global user.email my email@example.com
To create a Github for hosting a repository here are the following steps:
•	Go to the GitHub website: https://github.com/
•	Click on the "Sign up" button and follow the prompts to create a new account.
•	Verify your email address to complete the account setup.

Steps to be followed to initialize a Git repository for a project and a first commit:

•	Create a new directory for your project on your local machine.
•	Open a terminal or command prompt and navigate to the project directory.
•	Initialize a new Git repository by running the following command:
(a)	git init
•	Create a new file, for example, README.md, and add some content to it.
•	Add the file to the Git index (staging area) using the following command:
(a)	git add README.md
•	Commit the changes to the repository with a descriptive commit message:
(a)	git commit -m "Initial commit"

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
Step 1: Select Python Version
Install the latest version of python.
Step 2: Download Python Executable Installer
Visit the official Python website and navigate to the Downloads for Windows section. Download the desired version of Python, either the 32-bit or 64-bit installer.
Step 3: Run Executable Installer
Run the downloaded executable installer. The installation window will appear with two checkboxes:
1.	Admin privileges: This option allows you to install Python for all system users or just the current user. You can also change the installation folder.
2.	Add Python to PATH: This option adds the Python executable to the PATH environment variable, making it easier to access Python from the command line.
Step 4: Install Python
Click Install Now to start the installation. 
Step 5: Verify Python Installation
To verify that Python is installed correctly, follow these steps:
1.	Open the command prompt.
2.	Type python and press Enter. This should display the version of Python you installed.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
Verify pip Installation by:
1.	Open the command prompt.
2.	Type pip --V and press Enter. This should display the version of pip if it is installed successfully.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
Step 1: Visit the Official MySQL Website
1.	Open your preferred web browser and navigate to the official MySQL website.
2.	Click on the first download button to proceed to the download section.
Step 2: Go to the Downloads Section
1.	On the MySQL homepage, click on the "No thanks, just start my download" link to proceed to the download section.
Step 3: Run the Installer
1.	After downloading the MySQL.exe file, go to your Downloads folder and find the file.
2.	Double-click the file to run the installer.
Step 4: Choose Setup Type
1.	The installer will instruct you to choose the setup type. For most users, the "Developer Default" is suitable.
2.	Click "Next" to proceed.
Step 5: Check Requirements
1.	You might be prompted to install necessary MySQL software, typically Visual Code.
2.	The installer can auto-resolve some issues, but not in this case.
Step 6: MySQL Downloading
1.	Now that you're in the download section, click "Execute" to start downloading the components you selected.
2.	Wait a few minutes until all items show tick marks, indicating completion, before moving forward.
Step 7: MySQL Installation
1.	The downloaded components will be installed.
2.	Click "Execute" to start the installation process.
3.	MySQL will be installed on your Windows system.
4.	Then click "Next" to proceed.
Step 8: Navigate to Few Configuration Pages
1.	Proceed to "Product Configuration" > "Type and Networking" > "Authentication Method" pages by clicking the "Next" button.
Step 9: Create MySQL Accounts
1.	Create a password for the MySQL root user.
2.	Ensure it's strong and memorable.
3.	Click "Next" to proceed.
Step 10: Connect To Server
1.	Enter the root password, click Check.
2.	If it says "Connection succeed," you've successfully connected to the server.
Step 11: Complete Installation
1.	Once the installation is complete, click "Finish."
2.	Congratulations MySQL is now installed on your Windows system.
Step 12: Verify Installation
1.	To ensure a successful installation of MySQL, open the MySQL Command Line Client or MySQL Workbench, both available in your Start Menu.
2.	Log in using the root user credentials you set during installation.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
•	Node.js and NPM: Node.js and NPM are essential tools for web development. Node.js executes JavaScript code, and NPM installs JavaScript libraries.
•	VS Code: VS Code is a popular editor for writing code and executing it through an integrated terminal.
•	DevVM in Hyper-V: The DevVM in Hyper-V is a virtual machine that can be set up quickly and easily. It provides a robust and affordable development environment that can be replicated or cloned in case of a disaster.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
1.	Check the official repository for available extensions and plugins.
2.	Check for community-driven extensions and plugins.
3.	Check for official documentation on creating extensions.
4.	For VS Code check the custom editor API for customizable read or write editors.
5.	Explore the test editor integration options. 

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
Check for Hardware and Software Requirements
•	Computer: A Windows 10 laptop with 16 GB RAM and 512 GB SSD.
•	Operating System: Windows 10 Home.
•	Code Editor: Visual Studio Code (VS Code).
•	Integrated Development Environment (IDE): Visual Studio 2019.
•	Version Control System: Git.
•	Database Management System: MySQL.
Step-by-Step Setup Process

1. Install Visual Studio Code (VS Code)
1.	Download and Install VS Code:
•	Go to the official VS Code download page and download the latest version for Windows.
•	Run the installer and follow the prompts to install VS Code.

2. Install Visual Studio 2019
1.	Download and Install Visual Studio 2019:
•	Go to the official Visual Studio download page and download the Community edition for Windows.
•	Run the installer and follow the prompts to install Visual Studio 2019.

3. Install Git
1.	Download and Install Git:
•	Go to the official Git download page and download the latest version for Windows.
•	Run the installer and follow the prompts to install Git.

4. Install MySQL
1.	Download and Install MySQL:
•	Go to the official MySQL download page and download the latest version for Windows.
•	Run the installer and follow the prompts to install MySQL.

5. Configure VS Code
1.	Install Extensions:
•	Open VS Code and navigate to the Extensions panel.
•	Search for and install the following extensions:
•	Code Runner: For running code snippets directly in VS Code.
•	Debugger for Chrome: For debugging web applications.
•	GitLens: For enhanced Git integration.
•	Python: For Python development.
•	Configure Extensions:
•	Open the Command Palette in VS Code by pressing Ctrl + Shift + P.
•	Type Extensions: Configure and select the extension you want to configure.
•	Follow the prompts to configure the extension.

6. Configure Visual Studio 2019
1.	Install Additional Tools:
•	Open Visual Studio 2019 and navigate to the Tools menu.
•	Select Get Tools and Features.
•	Follow the prompts to install additional tools, such as the .NET Core SDK and the SQL Server Data Tools.

7. Configure Git
1.	Set Up Git:
•	Open Git Bash and navigate to the directory where you want to set up your Git repository.
•	Run the command git init to initialize a new Git repository.
•	Run the command git config --global user.name "Your Name" to set your Git username.
•	Run the command git config --global user.email "your_email@example.com" to set your Git email.

8. Troubleshooting Steps
1.	Common Issues and Solutions:
•	Error: "Git is not recognized as an internal or external command":
•	Ensure that Git is installed correctly and that the Git executable is in your system's PATH.
•	Error: "MySQL is not recognized as an internal or external command":
•	Ensure that MySQL is installed correctly and that the MySQL executable is in your system's PATH.
•	Error: "VS Code is not recognizing the Python extension":
•	Ensure that the Python extension is installed correctly and that the Python executable is in your system's PATH.

9. Final Check
1.	Verify Setup:
•	Open VS Code and ensure that all extensions are installed and configured correctly.
•	Open Visual Studio 2019 and ensure that all tools are installed and configured correctly.
•	Open Git Bash and ensure that Git is set up correctly.

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignmen
