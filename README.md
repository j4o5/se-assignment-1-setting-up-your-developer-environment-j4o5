[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15275948&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11
    Steps to install window 11
      (i) Format the drive and set the primary partition as active
      (ii)Copy windows setupon the usb flashdrive.
      (iii)connect th usb flashdrive to your PC, turn it on and press the key that opens boot device selection menu for the computer eg f10 and widows setup starts
      (iv)Follow the Steps and your operating system will be installed.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
  For Windows:
    Download:
     Go to the Visual Studio Code website.
     Click on the Download button for Windows.
    Install:
     Open the downloaded .exe file.
     Follow the setup wizard. Choose installation location and options.
     Click Install and wait for the process to complete.
    Configure:
     Launch VS Code.
     Go to Extensions (left sidebar) and search for any desired extensions (e.g., Python, JavaScript).
     Install extensions and configure settings under File > Preferences.
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com
    For Windows:
     Download Git:
       Visit the Git for Windows website.
       Click the download link to get the .exe file.
    Install Git:
       Run the downloaded .exe file.
       Follow the installation prompts. Accept default settings or customize them as needed.
       Select a text editor for Git to use (e.g., Vim, Notepad++).
    Verify Installation:
       Open Git Bash from the Start menu.
       Type git --version and press Enter to confirm Git is installed.
   Configure Git
    Set Your Username:
       Open a terminal or Git Bash.
       Run git config --global user.name "Your Name" (replace "Your Name" with your actual name).
    Set Your Email:
    Run'git config --global user.email "your.email@example.com" '(replace "your.email@example.com" with your actual email).
    Verify Configuration:
       Run git config --list to see all Git configurations.
   Creating a Github account
     Sign Up:
       Visit GitHub.
       Click on Sign up.
       Follow the prompts to create an account, entering your email, password, and username.
    Confirm Email:
       Check your email for a confirmation message from GitHub.
       Click the link in the email to verify your account.
4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.
    Installation on Windows
      Visit the link https://www.python.org/downloads/
    Double-click the executable file, which is downloaded;
      Select Customize installation and proceed.
      Click on the Add Path check box, it will set the Python path automatically.
      Follow the installation propmts until the end.
    Respective Compiler
    Install PyInstaller:
      Run pip install pyinstaller.
    Verify Installation:
      Run pyinstaller --version.
Create an Executable:
    In your project directory, run pyinstaller --onefile your_script.py.  

5. Install Package Managers:
   If applicable, install package managers like pip (Python).
    Download Python:
     Visit the Python official website.
     Download the installer for the latest version of Python.
    Run the Installer:
     Open the downloaded .exe file.
     Make sure to check the Add Python to PATH option to make Python and pip accessible from the command line.
     Select Install Now and follow the prompts.
    Verify pip Installation:
     Open Command Prompt.
     Type pip --version to confirm that pip is installed.
    Install pip Manually (if necessary):
     Download the get-pip.py script from the pip documentation.
     Open Command Prompt and navigate to the directory containing the script.
     Run python get-pip.py.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html
    Download MySQL Installer:
      Visit the MySQL Community Downloads page.
      Select the MySQL installer appropriate for your system.
    Run the Installer:
      Open the downloaded file and follow the installation prompts.
      Choose the Developer Default installation for a typical setup or Custom for specific configurations.
    Configure MySQL Server:
      Select the MySQL Server version to install.
      Choose the Standalone MySQL Server option.
    Setup Configuration:
      Choose Default Server configuration for simplicity.
      Set the Connectivity options, usually leaving defaults is fine.
      Set a root password and create a new MySQL user for your applications.
    Start MySQL Server:
      After installation, the MySQL server will start automatically.
      Use MySQL Workbench or Command Line to connect to the server.
    Verify Installation:
      Open Command Prompt.
      Run mysql -u root -p and enter your password to log in.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.
     Download Docker Desktop:
       Visit the Docker Desktop for Windows page.
       Download and run the installer.
     Install Docker Desktop:
       Follow the installation prompts.
       During installation, ensure WSL 2 is enabled if you are using Windows Subsystem for Linux.
     Start Docker Desktop:
       Launch Docker Desktop from the Start menu.
       Docker will start automatically and should show an icon in the system tray.
     Verify Installation:
       Open PowerShell or Command Prompt.
       Run docker --version to check the Docker version.
     Run a Test Container:
       Verify that Docker is working by running "docker run hello-world"
8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.
    Visual Studio Code:
      Open Extensions View:
        Click on the Extensions icon in the Activity Bar on the side of the window.
        Or ress Ctrl+Shift+X (Windows/Linpux) or Cmd+Shift+X (macOS).
      Browse Extensions:
        In the Extensions view, you can search for extensions by name or category.
        Popular categories include Programming Languages, Snippets, Linters, Themes, etc.
      Install an Extension:
        Click on an extension name to see more details.
        Click the Install button to add it to your VS Code.
      Manage Installed Extensions:
        Go to Extensions View and click on the Installed tab.
        You can enable, disable, update, or uninstall extensions from here.
      Configure Extensions:
        Some extensions may have settings you can configure. Access these via File > Preferences > Settings or by clicking the gear icon next to the extension.
      Recommended Extensions:
       Syntax Highlighting:
         Python: Python by Microsoft
         JavaScript/TypeScript: ESLint
       Linting:
         ESLint for JavaScript
         Pylint for Python
       Code Formatting:
         Prettier for JavaScript, TypeScript, CSS, and more.
         Black for Python
       Version Control Integration:
         GitLens for advanced Git capabilities
         GitHub Pull Requests and Issues

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 
     
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

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
