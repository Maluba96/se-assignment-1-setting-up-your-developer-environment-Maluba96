[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15282982&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   Windows Operating System is a computer program that manages all computer resources and uses a Graphical User Interface (GUI) that allows users to interact with the computer through icons, buttons, and visual menus, rather than using text commands like other operating systems

   In order to Install Windows OS on your Machine:

   - Purchase a Windows installation media ISO/DVD or download a windows 32 or 64 bit setup depending on your machine's compatibility    
   - Use a running computer to format a USB Drive with at least 5GB Storage space. Activate the primary partition on the USB flash
   - Copy the contents of the windows product DVD/ISO to the USB Flash drive
   - Connect the USB Drive to the designated Computer. Open the boots -device selection menu and install Windows to the new PC.

   Challenges faced include:
   - Getting into the bootstrap menu proves to be tricky especially whennot familiar with the process. The keys needed to access the menu vary depenging on the system. 
   
   This challenge was overcame by attempting the various keys e.g. F2, F12 until the menu was accessed

   - When the creating a bootable USB drive, data may be lost as a result. This can be frustrating especially if the data in the USB drive is important. 
   
   This problem is avoided by creating a backup of the data on the drive to ensure that important data is safe, even if the drive is accidentally formatted.
   

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

   A text editor is a type of computer program that enables users to create and edit a range of programming language files. An example of a text editor is Visual Studio Code.

   VS Code is a source code editing application that was developed by Microsoft. It aims to provide the tools a developer needs for a quick code-build-debug cycle 

   In order to download Visual Studio code first visit the Visual Studio Website. 
   - Download the VS Package specifically for the Operating System you use.
   - Go to your downloads on your computer and opene the .exe file
   - Start the installation by clicking Run and selecting next until you reach the install button. Select in stall then select Finish to Launch Visual Studio Code.
   - Open the VS Code Application and navigate to the Extensions to install extentions for your text editor.

   Challenges faced when setting up the text editor include:
   - VS COde requires for specific systems to be installed in your machine for it to operate. Example given, a windows operating system. 

   To overcome this, ensure that all necessary prerequisites are installed before trying to install VSCode e.g. ensuring that you have an Windows OS

   - VSCode may not be compatible with older operating systems or outdated hardware. 

   In such cases, upgrading the operating system or hardware may be necessary. To help prevent this, uconsider using a lightweight code editor like Visual Studio Code Portable or Atom instead.
  
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Version Control Systems are software toold that help software teams to track chages, manage changes, collaborate and maintain source code over time.
   Git is an example of a well known open source distributed version control system that can easily be installed and used on Windows.

   These are the steps to Install Git on Windows:

   - Visit the official Git website. Go to the latest version of Git for Windows and download it.
   - Go to your downloads and open the installer to run it. The prompts must be followed in order to complete the installlation process.
   - After it has been installed. Open the command prompt on your computer and run as an administrator.
   - Verify that git has been installed by typing the command
      git -- Version 
   A message will be displayed as shown in the example below:
      git version 2.45.2.windows.1

   - After installing Git configure Git by typing in your command prompt

      global user.name "Your Name" 
      global user.email "Your Email"

   These commands are used to set up your user name and email address associated with your projects. This sets your email address for all repositories you create and clone in the machine and also the commits you make on your local machine or push to remote reposotories through the machine's Secure Socket Shell (SSH) key.

   Setting up Version Control Systems on Windows can pose unique challenges:

   - One of the challenges is the compatibility of various VCS tools. Git was originally build for unix like systems and may not function optimally on windows without additional tools or configurations.

   To avoid this, ensure that you install Git for windows. It includes an environment like Unix and simplifies the installation and usage of Git on Windows.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

   Python is a general purpose language which is designed to be used in a range of applications. It is often used to build websites/software, automate tasks and conduct data analysis.

   Setting up Python Involves the following steps.
   - First visit the official Python Website and download the latest version of python for Windows. Be sure to choose the installer for your Version of Windows (32 bit or 64 bit)
   - Go to your downloads. Open and run the Python installer. Select the default python installer.
   - Set the path manually on your machine by openining the Edit the System Environment Variables application.
   - Click on Environment variables. Click on 'Path' and select edit.
   - Select 'New' and paste the path to your Python installation folder
   - Click ok to save the changes.
   - Verify that python was installed by opening the cmd application on your computer and running it as an administrator. Type the command

      python --version

   
   Setting up python on Windows can pose unique challenges:

   - Compatibility issues can be presented with various software packages required by certain libraries or dependencies not being included in the installer package.
   To overcome this type or setback, it is essential to look up the necessary prerequisites before attempting to setup. Seeking help from online communities such as Stack Overflow.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

    Package managers are tools that simplify the process of installing, managing and updating third libraries or packages. Pip is the default package installer for Python. 

    Setting up pip on Windows:

    - Open your Command Prompt and run as administrator. Check if python is installed. 
    - Check if the Python PATH has been added to the system's PATH environment.
    - On your command prompt, install pip by typing

      python -m ensurepip --default-pip
   
   This command will automatically check if pip is installed and install setuptols and wheel packages required by pip to function correctly.

   - Verify that pip is installed by typing in the command prompt

      pip --version

   During the set up process of Pip on windows, users may face challenges.

   - Firewall setting can block internet access required for downloading packages from PyPI.

   This can be resolved by configuring firewall settings accordingly.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   MySQL is a relational database management system. It is open source system and it includes numerous features.

   MySqL installer for windows provides a friendly user interface which makes it easy to navigate and control the installation process.

   The following aare steps to install MySql for windows:

   - Go to your browser and search for 'MySql'. Navigate to the website and choose the mysql package you want to download.
   - Select the download link to download the file. Then execute the MySql installer file from the download folder.
   - Accept the license agreement terms. You can select predefined products that are goig to be installed or customize your own set up.
   - When you get to 'Accounts and Roles', enter a password for your MySql root user and click next.
   - After applying the necessary configurations to suit your environment, finish the installation.
   - To verify if MySql is installed. Go to your start button and search for Mysql to see the applications.

   Challenges faced include:

   - MySql has prerequisites for its compatibility. These include, sufficient disk space, memory and a compatible process.

   It is important to ensure that the system meets the prerequisites before installing MySql.

   - Firewalls block incomming connections to the database server. 
   To fix this, configure the firewall to allow traffic on the required ports. The default port is 3306.



7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.ins 

   Plugins and extensions are optional features that can be added to the computer graphics software to expand it's functionality, performance or creativity. 

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


[def]: image.png