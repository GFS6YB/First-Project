# First-Project
lets start
This project provides a Bash script for automating the installation of Jenkins on an Ubuntu system. Jenkins is an open-source automation server widely used for Continuous Integration and Continuous Delivery (CI/CD) pipelines. This script streamlines the installation process, saving you time and effort.

Key Features:
Automated Installation:
The script automates the entire installation process, including adding the Jenkins repository, installing Java OpenJDK, and starting the Jenkins service.
Improved Efficiency:
Saves you time by eliminating the need for manual configuration through the terminal.
Clarity and Comments:
The script includes comments to explain each step, making it easy to understand and modify if needed.
Security Note:
The script retrieves the initial password from the file system. Remember to change the password after initial setup for security reasons.
How to Use:
Copy the Script:
Copy the provided script content (refer to the script in the previous response) into a new file named install_jenkins.sh.
Make the Script Executable: Open a terminal in the directory containing the script and run the following command:
Bash
chmod +x install_jenkins.sh
Use code with caution.
Run the Script: Execute the script with sudo privileges:
Bash
sudo ./install_jenkins.sh
Use code with caution.
Access Jenkins: Once the script finishes, you can access the Jenkins web interface at http://localhost:8080. The initial password to unlock Jenkins will be located at /var/lib/jenkins/secrets/initialAdminPassword. Remember to change this password promptly!
