[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15221158&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   

Check System Requirements

Before downloading and installing Windows 11, ensure that your system meets the minimum requirements:

- Processor: 1 gigahertz (GHz) or faster with at least 2 cores on a compatible 64-bit processor or System on a Chip (SoC)
- RAM: 4 GB or more
- Storage: 64 GB or larger storage device
- System Firmware: UEFI, Secure Boot capable
- TPM: Trusted Platform Module (TPM) version 2.0
- Graphics Card: DirectX 12 compatible graphics / WDDM 2.x
- Display: >9” with HD Resolution (720p)
- Internet Connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

Backup Your Data

It's important to back up your data before installing a new operating system. You can use an external hard drive, cloud storage, or another backup solution to save your important files.

Download Windows 11

(1). Visit the Windows 11 Download Page:
   - Go to the [Windows 11 download page](https://www.microsoft.com/software-download/windows11).

(2). Choose Your Download Option:
   - You can either create installation media (USB flash drive or DVD) or download an ISO file.
   - For this guide, we’ll focus on creating a bootable USB drive.

(3). Download the Media Creation Tool:
   - Click on Download now under "Create Windows 11 Installation Media".
   - Run the Media Creation Tool once downloaded.

Create Installation Media

(1). Run the Media Creation Tool:
   - Accept the license terms.
   - Select Create installation media (USB flash drive, DVD, or ISO file) for another PC, then click Next.

(2). Select Language, Edition, and Architecture:
   - Choose your language, edition, and architecture (64-bit).

(3). Choose USB Flash Drive:
   - Select USB flash drive and click Next.
   - Insert a USB flash drive with at least 8 GB capacity and select it from the list, then click Next.

(4). Download and Create Media:
   - The tool will download Windows 11 and create the installation media on your USB drive. This may take some time.

Install Windows 11

(1). Boot from the USB Drive:
   - Insert the USB flash drive into the computer where you want to install Windows 11.
   - Restart the computer and boot from the USB drive. This usually involves pressing a key (such as F2, F12, Delete, or Esc) immediately after turning on the computer to enter the boot menu.

(2). Begin Installation:
   - Select your language, time, and keyboard preferences, then click Next.
   - Click Install now.

(3). Enter Product Key:
   - If you have a Windows 11 product key, enter it. Otherwise, select I don’t have a product key and proceed (you can activate Windows later).

(4). Select Edition:
   - Choose the edition of Windows 11 that you want to install and click Next.

(5). Accept License Terms:
   - Read and accept the license terms, then click Next.

(6). Choose Installation Type:
   - Select Custom: Install Windows only (advanced) for a clean installation.

(7). Select Partition:
   - Choose the partition where you want to install Windows 11. If you're doing a clean install, you may want to delete existing partitions (this will erase all data on those partitions) and create new ones.
   - Click Next to start the installation.

(8). Complete Installation:
   - Windows 11 will install, and your computer will restart several times during the process.
   - Follow the on-screen instructions to set up your preferences and create a user account.

Post-Installation Setup

(1). Install Updates:
   - Once Windows 11 is installed, check for updates by going to Settings > Windows Update and installing any available updates.

(2). Install Drivers:
   - Install the necessary drivers for your hardware components. Most drivers will be automatically detected, but you may need to manually download some from the manufacturer’s website.
(3). Restore Data:
   - Restore your backed-up data to your new Windows 11 installation.

(4). Install Applications:
   - Reinstall your applications and configure your development environment as needed.



2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


(a). Open your web browser and navigate to the [official Visual Studio Code website](https://code.visualstudio.com/).

(b). Click on the Download for Windows button. This will download the VSCode installer (VSCodeUserSetup-x64-x.y.z.exe, where x.y.z is the version number).

 Install VSCode

(1). Locate the downloaded installer in your Downloads folder and double-click to run it.

(2). Follow the installation wizard:
   - Accept the License Agreement.
   - Select Destination Location: By default, it installs to C:\Users\<Your Username>\AppData\Local\Programs\Microsoft VS Code.
   - Select Start Menu Folder: Leave the default or customize it.
   - Select Additional Tasks: It's recommended to check the following options:
     - Create a desktop icon.
     - Add "Open with Code" action to Windows Explorer file context menu.
     - Add "Open with Code" action to Windows Explorer directory context menu.
     - Register Code as an editor for supported file types.
     - Add to PATH (this allows you to open VSCode from the command line).
   - Click Install to begin the installation process.

Launch VSCode

(1). Once the installation is complete, ensure the option to Launch Visual Studio Code is checked and click Finish.

(2). VSCode will open, displaying a welcome screen with various options and tips.

Customize VSCode by installing extensions


Extensions enhance the functionality of VSCode. Common extensions include:

(1). Python:
   - Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
   - Search for "Python" and click Install on the official Python extension by Microsoft.

(2). C/C++:
   - Search for "C/C++" and install the extension by Microsoft.

(3). ESLint (for JavaScript/TypeScript):
   - Search for "ESLint" and install the extension by Dirk Baeumer.

(4). Prettier (code formatter):
   - Search for "Prettier - Code formatter" and install the extension by Prettier.

Configuring Settings

(1). Open Settings:
   - Go to File > Preferences > Settings or press Ctrl+,.

(2). Common Settings:
   - Font Size: Adjust by searching for Editor: Font Size.
   - Theme: Change the color theme by searching for Color Theme and selecting your preferred theme.
   - Auto Save: Enable auto-save by searching for Files: Auto Save and setting it to afterDelay.
Configuring Python

(1). Interpreter:
   - Press Ctrl+Shift+P to open the Command Palette.
   - Type Python: Select Interpreter and choose the appropriate Python interpreter.

(2). Linting:
   - Open settings (Ctrl+,) and search for Linting.
   - Enable Python > Linting: Enabled and select your preferred linter (e.g., Pylint).

Troubleshooting

(1). Extensions Not Installing:
   - Ensure you have a stable internet connection.
   - Check for any proxy settings that might be blocking access.

(2). Python Interpreter Not Found:
   - Ensure Python is installed and added to your system PATH.
   - Verify by running python --version in a command prompt.

(3). Code Not Running:
   - Check the integrated terminal settings.
   - Ensure the correct interpreter or compiler is selected.

Finalize Setup

(1). Open a Project Folder:
   - Go to File > Open Folder and select your project directory.

(2). Version Control:
   - If using Git, ensure it's installed and configured.
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl+Shift+G.

(3). Workspace Settings:
   - Configure workspace-specific settings by opening the settings (Ctrl+,), switching to the Workspace tab, and adjusting as needed.

Explore and Enhance

(1). Explore Built-in Features:
   - Utilize IntelliSense, debugging, and integrated terminal.

(2). Install Additional Extensions:
   - Explore the Extensions marketplace for more tools relevant to your workflow.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com.


Install Git

(1). Download Git:
   - Go to the [Git download page](https://git-scm.com/).
   - Click on the Windows link to download the Git installer.

(2). Run the Installer:
   - Locate the downloaded installer and double-click to run it.
   - Follow the installation wizard:
     - Select Destination Location: Leave the default or choose a custom location.
     - Select Components: Leave the default options selected.
     - Adjusting Your PATH Environment: Select "Git from the command line and also from 3rd-party software".
     - Choosing the SSH executable: Use the bundled OpenSSH.
     - Choosing HTTPS transport backend: Use the OpenSSL library.
     - Configuring the line ending conversions: Checkout Windows-style, commit Unix-style line endings.
     - Configuring the terminal emulator: Use MinTTY (the default terminal of MSYS2).
     - Configuring extra options: Leave the default options selected.
   - Click Install to complete the installation.

(3). Verify Installation:
   - Open Command Prompt or PowerShell.
   - Type git --version and press Enter to verify that Git is installed correct
   - 


Configure Git

(1). Set Up Your User Name and Email:
   - Open Command Prompt or PowerShell.
   - Run the following commands, replacing <Your Name> and <your.email@example.com> with your information:
    
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     
(2). Verify Configuration:
   - Run the following command to see the configured values:
    
     git config --list
     
Create a GitHub Account

(1). Sign Up for GitHub:
   - Go to [GitHub](https://github.com/).
   - Click on Sign up.
   - Fill in the required information (username, email, password) and complete the sign-up process.

(2). Confirm Your Email:
   - Check your email for a confirmation message from GitHub and follow the instructions to verify your email address.
Create a Repository on GitHub

(1). Log In to GitHub:
   - Log in to your GitHub account.

(2). Create a New Repository:
   - Click on the + icon in the upper right corner and select New repository.
   - Fill in the repository details:
     - Repository name: Choose a name for your repository.
     - Description: (Optional) Add a description for your repository.
     - Visibility: Choose between public (anyone can see this repository) or private (you choose who can see this repository).
     - Initialize this repository with a README: Check this box if you want to add a README file (you can always add one later).
   - Click Create repository.

Initialize a Git Repository Locally

(1). Open a Terminal:
   - Open Command Prompt or PowerShell.

(2). Navigate to Your Project Directory:
   - Use the cd command to navigate to your project directory. For example:
    
     cd path/to/your/project
     
(3). Initialize a Git Repository:
   - Run the following command to initialize a new Git repository:
    
     git init
     
(4). Add Files to the Repository:
   - Add all files to the staging area:
    
     git add .
     
(5). Make Your First Commit:
   - Commit the files with a commit message:
    
     git commit -m "Initial commit"
     
Link Your Local Repository to GitHub

(1). Copy the Repository URL:
   - Go to your repository on GitHub.
   - Click the Code button and copy the URL (choose HTTPS).

(2). Add the Remote Repository:
   - In Command Prompt or PowerShell, run the following command, replacing <URL> with the copied URL:
    
     git remote add origin <URL>
     
(3). Push Your Changes to GitHub:
   - Push your changes to the GitHub repository:
    
     git push -u origin master.



4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  
Download Python

(1). Visit the Python Official Website:
   - Go to the [Python download page](https://www.python.org/downloads/).

(2). Select the Latest Version:
   - The website will typically recommend the latest version of Python for your operating system. Click the Download Python X.X.X button.

Install Python

(1). Run the Installer:
   - Locate the downloaded installer (usually in your Downloads folder) and double-click to run it.

(2). Customize Installation:
   - Add Python to PATH: Before you click on "Install Now," make sure to check the box that says Add Python X.X to PATH. This will make it easier to run Python from the command line.
   - Click Install Now to start the installation process with the default settings.

(3). Advanced Options (Optional):
   - If you need to customize the installation (for example, if you need to install Python for all users), click on Customize installation. 
   - Select the features you need and choose the installation directory if necessary.

(4). Complete the Installation:
   - The installer will install Python and its components. Once completed, click on Close.

Verify Python Installation

(1). Open Command Prompt:
   - Press Win + R, type cmd, and press Enter to open the Command Prompt.

(2). Check Python Version:
   - Type python --version and press Enter. You should see the installed Python version displayed.
   - Also, check pip (Python's package installer) by typing pip --version.




5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Install Necessary Python Packages

(1). Using pip:
   - Python comes with pip, the package installer. You can use it to install necessary libraries and tools for your project.
   - For example, to install popular packages like requests and numpy, you would run:
    
     pip install requests numpy
     
(2). Create a Virtual Environment (Optional but recommended):
   - It's a good practice to create a virtual environment for your project to manage dependencies.
   - Create a virtual environment:
    
     python -m venv myenv
     
   - Activate the virtual environment:
     - On Windows:
      
       myenv\Scripts\activate
       
     - On macOS and Linux:
      
       source myenv/bin/activate
       
   - Install your project's dependencies within this virtual environment using pip.


Install Integrated Development Environment (IDE)

(1). Visual Studio Code (VSCode):
   - Download and install VSCode as outlined in the previous guide.
   - Install the Python extension for VSCode for a better development experience:
     - Open VSCode.
     - Go to the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
     - Search for "Python" and install the extension provided by Microsoft.

(2). Configure VSCode for Python:
   - Open a Python file in VSCode.
   - If you haven't selected a Python interpreter yet, you will see a prompt to select one. Click on it and choose the Python interpreter from the virtual environment or the global one you installed earlier.
   - You can also manually select the interpreter by pressing Ctrl+Shift+P, typing Python: Select Interpreter, and choosing the appropriate one.

Test Your Setup

(1). Write a Simple Python Script:
   - Create a new file named test.py and add the following code:
    
     print("Hello, Python!")
     
(2). Run the Script:
   - In Command Prompt or the integrated terminal in VSCode, navigate to the directory where test.py is located and run:
    
     python test.py
     
   - You should see Hello, Python! printed in the terminal.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Download MySQL Installer

(1). Visit the MySQL Download Page:
   - Go to the [MySQL Community Downloads page](https://dev.mysql.com/downloads/windows/installer/5.7.html).

(2). Download the MySQL Installer:
   - Choose the appropriate MySQL Installer (Web or Full).
   - Click on the Download button for the installer.

(3). Sign Up or Log In:
   - You can log in to your Oracle account or click on No thanks, just start my download to proceed without logging in.
Install MySQL

(1). Run the Installer:
   - Locate the downloaded installer file (usually in your Downloads folder) and double-click to run it.

(2). Choose Setup Type:
   - Select a setup type. For most users, Developer Default or Full is recommended, as it installs all the necessary components.

(3). Check Requirements:
   - The installer will check for any missing dependencies. Click Next to continue.

(4). Installation Path:
   - Choose the installation path if you want to change the default location. Otherwise, leave it as is and click Next.

(5). Installation Progress:
   - Click Execute to start the installation. The installer will download and install the selected components.

Configure MySQL Server

(1). Type and Networking:
   - Configure the server as a Standalone MySQL Server.
   - Select Development Machine for the configuration type.
   - Leave the port as the default (3306) and ensure that TCP/IP is selected.
   - Click Next.

(2). Authentication Method:
   - Choose the appropriate authentication method. Use Strong Password Encryption is recommended.
   - Click Next.

(3). Accounts and Roles:
   - Set the root password. Make sure to remember this password as it is critical for accessing your MySQL server.
   - Optionally, you can add additional MySQL user accounts.
   - Click Next.

(4). Windows Service:
   - Configure MySQL to run as a Windows Service. This will start the MySQL server automatically when Windows starts.
   - Set the service name and ensure that Start the MySQL Server at System Startup is checked.
   - Click Next.

(5). Apply Configuration:
   - Click Execute to apply the configuration settings.


Complete Installation

(1). Installation Complete:
   - After the installation and configuration steps are complete, click Finish.

Verify MySQL Installation

(1). Open MySQL Command Line Client:
   - Search for "MySQL Command Line Client" in the Start menu and open it.

(2). Log In to MySQL:
   - Enter the root password you set during the installation.

(3). Run a Simple Command:
   - Verify the installation by running a simple command, such as:
    
     SHOW DATABASES;
     
   - This should list the default databases installed with MySQL.

Install MySQL Workbench (Optional but Recommended)

(1). Download MySQL Workbench:
   - You can download MySQL Workbench from the [MySQL Community Downloads page](https://dev.mysql.com/downloads/workbench/).

(2). Install MySQL Workbench:
   - Run the installer and follow the on-screen instructions to complete the installation.

(3). Configure MySQL Workbench:
   - Open MySQL Workbench.
   - Create a new connection to your MySQL server using the root user and the password you set.
   - Test the connection to ensure everything is working correctly.


7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

   
Download and Install Docker

(1). Visit Docker's Official Website:
   - Go to the [Docker download page](https://www.docker.com/products/docker-desktop).

(2). Download Docker Desktop:
   - Click the Download for Windows button to get the Docker Desktop installer.

(3). Run the Installer:
   - Locate the downloaded installer (usually in your Downloads folder) and double-click to run it.

(4). Follow the Installation Wizard:
   - The Docker Desktop installer will guide you through the installation process. Follow the on-screen instructions.
   - When prompted, ensure you select the option to enable WSL 2 features if you are on Windows 10 or higher. This will provide better performance and compatibility.

(5). Complete the Installation:
   - Once the installation is complete, Docker Desktop will ask you to log in or create a Docker account.


Verify Docker Installation

(1). Start Docker Desktop:
   - Open Docker Desktop from the Start menu.

(2). Check Docker Version:
   - Open Command Prompt or PowerShell.
   - Run the following command to check if Docker is installed correctly:
    
     docker --version
     
   - You should see the Docker version information.

Set Up a Dockerized Development Environment

(1). Create a Project Directory:
   - Create a new directory for your project. For example:
    
     mkdir my-docker-project
     cd my-docker-project
     
(2). Create a Dockerfile:
   - A Dockerfile is a text file that contains the instructions to build a Docker image for your project.
   - Create a file named Dockerfile in your project directory and add the following example content:
    
     
     FROM python:3.10-slim

     
     WORKDIR /app

     
     COPY . /app

     
     RUN pip install --no-cache-dir -r requirements.txt

     
     EXPOSE 80

     
     ENV NAME World

     
     CMD ["python", "app.py"]
     
(3). Create Requirements File:
   - If your project requires Python packages, create a requirements.txt file in your project directory and list your packages:
    
     flask
     requests
     
(4). Create a Sample Python Application:
   - Create a app.py file in your project directory with a simple Flask application:
    
     from flask import Flask
     app = Flask(__name__)

     @app.route('/')
     def hello():
         return "Hello, Docker!"

     if __name__ == "__main__":
         app.run(host='0.0.0.0', port=80)
     
Build and Run the Docker Container

(1). Build the Docker Image:
   - In your project directory, build the Docker image using the following command:
    
     docker build -t my-docker-app .
     
(2). Run the Docker Container:
   - Run the Docker container from the image you just built:
    
     docker run -p 4000:80 my-docker-app
     
   - This command maps port 80 in the container to port 4000 on your host machine.

(3). Test the Application:
   - Open a web browser and go to http://localhost:4000.
   - You should see "Hello, Docker!" displayed, indicating your containerized application is running.

Manage Docker Containers

(1). List Running Containers:
   - To see all running containers, use:
    
     docker ps
     
(2). Stop a Running Container:
   - To stop a running container, use:
    
     docker stop <container_id>
     
   - Replace <container_id> with the actual container ID from the docker ps output.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Extensions enhance the functionality of VSCode. Common extensions include:

(1). Python:
   - Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
   - Search for "Python" and click Install on the official Python extension by Microsoft.

(2). C/C++:
   - Search for "C/C++" and install the extension by Microsoft.

(3). ESLint (for JavaScript/TypeScript):
   - Search for "ESLint" and install the extension by Dirk Baeumer.

(4). Prettier (code formatter):
   - Search for "Prettier - Code formatter" and install the extension by Prettier.

Configuring Settings

(1). Open Settings:
   - Go to File > Preferences > Settings or press Ctrl+,.

(2). Common Settings:
   - Font Size: Adjust by searching for Editor: Font Size.
   - Theme: Change the color theme by searching for Color Theme and selecting your preferred theme.
   - Auto Save: Enable auto-save by searching for Files: Auto Save and setting it to afterDelay.
Configuring Python

(1). Interpreter:
   - Press Ctrl+Shift+P to open the Command Palette.
   - Type Python: Select Interpreter and choose the appropriate Python interpreter.

(2). Linting:
   - Open settings (Ctrl+,) and search for Linting.
   - Enable Python > Linting: Enabled and select your preferred linter (e.g., Pylint).


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
