
## Setup Development Environment

### Objective
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

### Tasks and Solutions

1. **Select Your Operating System (OS):**
   - Chosen OS: **Windows 11**
   - Download and Install: [Windows 11](https://www.microsoft.com/software-download/windows11)
   - **Installation Completed.**

2. **Install a Text Editor or Integrated Development Environment (IDE):**
   - Chosen IDE: **Visual Studio Code**
   - Download and Install: [Visual Studio Code](https://code.visualstudio.com/Download)
   - **Installation Completed.**

3. **Set Up Version Control System:**
   - Install Git:
     ```bash
     sudo apt-get install git
     ```
   - Configure Git:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "youremail@example.com"
     ```
   - Create a GitHub account: [GitHub](https://github.com)
   - Initialize a Git repository:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git remote add origin https://github.com/yourusername/your-repo.git
     git push -u origin master
     ```
   - **Configuration and initial commit completed.**

4. **Install Necessary Programming Languages and Runtimes:**
   - Install Python:
     - Download and Install: [Python](https://www.python.org/downloads/)
     - Verify Installation:
       ```bash
       python --version
       ```
   - **Python installation and verification completed.**

5. **Install Package Managers:**
   - Install pip:
     ```bash
     sudo apt-get install python3-pip
     ```
   - Verify Installation:
     ```bash
     pip --version
     ```
   - **pip installation and verification completed.**

6. **Configure a Database (MySQL):**
   - Download and Install: [MySQL](https://dev.mysql.com/downloads/windows/installer/5.7.html)
   - **MySQL installation completed.**

7. **Set Up Development Environments and Virtualization (Optional):**
   - Install Docker:
     - Download and Install: [Docker](https://www.docker.com/products/docker-desktop)
     - Verify Installation:
       ```bash
       docker --version
       ```
   - **Docker installation and verification completed.**

8. **Explore Extensions and Plugins:**
   - Extensions for Visual Studio Code:
     - Python
     - GitLens
     - Prettier - Code formatter
     - ESLint
     - Docker
   - **Extensions installed and configured.**

9. **Document Your Setup:**
   - Comprehensive document outlining steps, configurations, customizations, and troubleshooting steps (included in this README).

### Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary (included in this README).
- GitHub repository link: [Your Repository](https://github.com/yourusername/your-repo)
- Reflection on the challenges faced during setup and strategies employed to overcome them.

### Reflection
During the setup process, I encountered several challenges, including:
- **Installation Issues:** Initially, there were problems with the MySQL installation due to incompatible versions. I resolved this by following online troubleshooting guides and ensuring that all dependencies were correctly installed.
- **Configuration Errors:** Configuring Git was challenging due to incorrect email settings, which I fixed by carefully following Git documentation.
- **Tool Selection:** Choosing the right extensions for Visual Studio Code was time-consuming. I researched and tested various extensions before selecting the ones that best suited my workflow.

By documenting each step and troubleshooting effectively, I was able to successfully set up a productive developer environment.

### Conclusion
This assignment has provided me with a solid understanding of setting up a development environment. The experience gained through resolving installation and configuration issues has been invaluable for future projects.

---
