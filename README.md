[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15295069&assignment_repo_type=AssignmentRepo)
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

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.


<br>
<br>



#ANSWER

# Developer Environment Setup Guide

## 1. Select Your Operating System (OS)

Choose an operating system that best suits your preferences and project requirements. For this guide, we will focus on installing Windows 11.

### Download and Install Windows 11

1. **Download Windows 11**: Visit [Microsoft's download page](https://www.microsoft.com/software-download/windows11) to get the Windows 11 ISO file.

2. **Installation Process**:

   Since my Dell laptop specs don’t support Windows 11, I used the following method:

   - **A. Activate Secure Boot and TPM**:
     - Restart and enter BIOS setup to activate Secure Boot and TPM. *(Screenshots from BIOS setup cannot be provided)*

   - **B. Download Windows 11 ISO**:
     - Download the ISO file from the [Microsoft website](https://www.microsoft.com/software-download/windows11).
     ![](Windows 11 Screenshot)

   - **C. Download Rufus Software**:
     - Download and install Rufus to create bootable media.

   - **D. Partition Disk Space**:
     - Use Disk Management to create a new volume for Windows 11.

   - **E. Create Bootable Media**:
     - Insert your flash drive and use Rufus to create bootable media by selecting the flash drive and ISO file.

   - **F. Configure Rufus Parameters**:
     - Bypass TPM2 and Secure Boot checks due to system non-compatibility.

   - **G. Install Windows 11**:
     - Close all running programs and plug the USB flash drive into your computer to start the installation. Follow the on-screen instructions.

   - **H. Boot from Flash Drive**:
     - Restart the laptop and boot from the flash drive. Select your language.

   - **I. Install Windows 11**:
     - Click 'Next' and 'Install Now'.

   - **J. Activate Windows**:
     - Enter the activation key when prompted.

   - **K. Select Windows Version**:
     - Choose the desired version of Windows 11.

   - **L. Accept License Agreement**:
     - Agree to the license terms and click 'Next'.

   - **M. Custom Install**:
     - Choose 'Custom Install' and select the volume created earlier.

   - **N. Complete Installation**:
     - The installation process begins, resulting in a dual-boot setup with Windows 10.

## 2. Install a Text Editor or IDE

### Download and Install Visual Studio Code

1. **Download Visual Studio Code**: Visit [Visual Studio Code download page](https://code.visualstudio.com/Download).

2. **Installation Process**:

   - **A. Download and Run Installer**:
     - Go to the download page and run the installer.

   - **B. License Agreement**:
     - Agree to the license terms.

   - **C. Installation Location**:
     - Accept the default installation location and click 'Next'.

   - **D. Start Menu Folder**:
     - Choose or create a Start Menu folder.

   - **E. Additional Tasks**:
     - Choose to create a desktop icon and add other capabilities.

   - **F. Complete Installation**:
     - Review the summary of selections and click 'Install'.

   - **G. Install Extensions**:
     - Install necessary extensions as taught in classes.

## 3. Set Up Version Control System

### Install and Configure Git

1. **Download Git**: Go to the [Git website](https://git-scm.com/downloads) and download the version for Windows.

2. **Installation Process**:

   - **A. Run Installer**:
     - Double-click the installer, agree to the license, and click 'Next'.

   - **B. Installation Location**:
     - Agree to the default location and click 'Next'.

   - **C. Select Components**:
     - Add components like additional icons.

   - **D. Choose Default Editor**:
     - Select Notepad++ as the default editor.

   - **E. Complete Installation**:
     - Agree to default options and complete the installation.

### Initialize a Git Repository

1. **Create a New Repository on GitHub**:

   - **a. Log In to GitHub**:
     - Go to [GitHub](https://github.com) and log in.

   - **b. Create Repository**:
     - Click the '+' icon and select 'New repository'.

   - **c. Enter Details**:
     - Name your repository, add a description, choose visibility (public/private), and do not initialize with README, .gitignore, or license.

   - **d. Create Repository**:
     - Click 'Create repository'.

2. **Initialize Repository Locally**:

   - **a. Open Git Bash**:
     - Open Git Bash on your computer.

   - **b. Navigate Directory**:
     - Use `cd /path/to/your/directory` to navigate.

   - **c. Initialize Git**:
     - Run `git init`.

   - **d. Add Files**:
     - Create and add files. For example, use `vi README.md` to create a README file.

   - **e. Stage Files**:
     - Run `git add .`.

   - **f. Commit Files**:
     - Commit files with `git commit -m "My first commit"`.

3. **Connect to GitHub Repository**:

   - **a. Get Repository URL**:
     - Copy the repository URL from GitHub.

   - **b. Add Remote Repository**:
     - Run `git remote add origin [URL]`.

   - **c. Push to GitHub**:
     - Push commits using `git push -u origin master`.

4. **Verify**:
   - Refresh GitHub to see your files and commit message.

## 4. Install Necessary Programming Languages and Runtimes

### Install Python

1. **Download Python**:
   - Visit [Python's official website](http://www.python.org) and download the installer.

2. **Installation Process**:

   - **a. Run Installer**:
     - Run the executable file.

   - **b. Customize Installation**:
     - Check "Add Python to PATH" and select 'Customize installation'.

   - **c. Optional Features**:
     - Leave optional features as default and click 'Next'.

   - **d. Advanced Options**:
     - Choose "Install for all users" and click 'Install'.

   - **e. Complete Installation**:
     - Wait for installation to complete and click 'Close'.

3. **Verify Installation**:
   - Open Command Prompt and check Python version with `python --version`.

4. **Install Packages**:
   - Use pip to install packages, e.g., `pip install matplotlib` and `python -m pip install Django`.

5. **Upgrade pip**:
   - Run `python -m pip install --upgrade pip`.

## 5. Configure a Database (MySQL)

### Download and Install MySQL

1. **Download MySQL Installer**:
   - Go to [MySQL download page](https://dev.mysql.com/downloads/windows/installer/5.7.html) and download the installer.

2. **Installation Process**:

   - **a. Run Installer**:
     - Open the MySQL Installer file.

   - **b. Accept License**:
     - Read and accept the Oracle license agreement.

   - **c. Select Installation Type**:
     - Choose "Developer Default" and click 'Next'.

   - **d. Resolve Inconsistencies**:
     - Install additional software if prompted and click 'Execute'.

   - **e. Begin Installation**:
     - Click 'Next' and 'Execute' to start installation.

3. **Configure MySQL Server**:

   - **a. High Availability**:
     - Select "Standalone MySQL Server" and click 'Next'.

   - **b. Type and Networking**:
     - Choose "Development Computer" and keep default port. Click 'Next'.

   - **c. Authentication Method**:
     - Select "Use Strong Password Encryption" and click 'Next'.

   - **d. Accounts and Roles**:
     - Set a root password and click 'Next'.

   - **e. Windows Service**:
     - Configure MySQL to run as a Windows Service with "Standard System Account". Click 'Next'.

   - **f. Apply Configuration**:
     - Click 'Execute' and then 'Finish'.

4. **Start MySQL Server**:

   - **a. Open Command Prompt**:
     - Run Command Prompt as an administrator.

   - **b. Start MySQL**:
     - Navigate to the MySQL bin directory and run `mysqld --console`.

5. **Stop MySQL Server**:

   - **a. Stop Server**:
     - Use `mysqladmin -u root shutdown` to stop MySQL server.

## 6. Set Up Development Environments and Virtualization (Optional)

Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments.

## 7. Explore Extensions and Plugins

Enhance functionality of your text editor or IDE with extensions and plugins. Examples include:

- **Code Runner**
- **Dart**
- **Flutter**
- **Pylance**

Install these from the extension section of the side pane in your IDE.

## 8. Document Your Setup

Create a comprehensive document outlining all setup steps, configurations, customizations, and troubleshooting encountered during the process.

---

