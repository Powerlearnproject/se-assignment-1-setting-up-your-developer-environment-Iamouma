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

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


(a). Open your web browser and navigate to the [official Visual Studio Code website](https://code.visualstudio.com/).
(b). Click on the Download for Windows button. This will download the VSCode installer (VSCodeUserSetup-x64-x.y.z.exe, where x.y.z is the version number).

 Install VSCode

1. Locate the downloaded installer in your Downloads folder and double-click to run it.
2. Follow the installation wizard:
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

### Step 3: Launch VSCode

1. Once the installation is complete, ensure the option to Launch Visual Studio Code is checked and click Finish.
2. VSCode will open, displaying a welcome screen with various options and tips.

### Step 4: Customize VSCode

#### Installing Extensions

Extensions enhance the functionality of VSCode. Common extensions include:

1. Python:
   - Open the Extensions view by clicking the Extensions icon in the Activity Bar on the side of the window or pressing Ctrl+Shift+X.
   - Search for "Python" and click Install on the official Python extension by Microsoft.

2. C/C++:
   - Search for "C/C++" and install the extension by Microsoft.

3. ESLint (for JavaScript/TypeScript):
   - Search for "ESLint" and install the extension by Dirk Baeumer.

4. Prettier (code formatter):
   - Search for "Prettier - Code formatter" and install the extension by Prettier.

#### Configuring Settings

1. Open Settings:
   - Go to File > Preferences > Settings or press Ctrl+,.

2. Common Settings:
   - Font Size: Adjust by searching for Editor: Font Size.
   - Theme: Change the color theme by searching for Color Theme and selecting your preferred theme.
   - Auto Save: Enable auto-save by searching for Files: Auto Save and setting it to afterDelay.

#### Configuring Python

1. Interpreter:
   - Press Ctrl+Shift+P to open the Command Palette.
   - Type Python: Select Interpreter and choose the appropriate Python interpreter.

2. Linting:
   - Open settings (Ctrl+,) and search for Linting.
   - Enable Python > Linting: Enabled and select your preferred linter (e.g., Pylint).

### Step 5: Troubleshooting

#### Common Issues

1. Extensions Not Installing:
   - Ensure you have a stable internet connection.
   - Check for any proxy settings that might be blocking access.

2. Python Interpreter Not Found:
   - Ensure Python is installed and added to your system PATH.
   - Verify by running python --version in a command prompt.

3. Code Not Running:
   - Check the integrated terminal settings.
   - Ensure the correct interpreter or compiler is selected.

### Step 6: Finalize Setup

1. Open a Project Folder:
   - Go to File > Open Folder and select your project directory.

2. Version Control:
   - If using Git, ensure it's installed and configured.
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl+Shift+G.
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

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
