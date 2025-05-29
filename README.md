# Bash-scripting-devops
 
This is my first Readme on learning Devops
This sis my first assignment on Devops. 

Task: Linux User and Group Management Script with Logging.
Difficulty: Easy

Skills practiced: User and group management commands (useradd, usermod, userdel, groupadd, groupdel, passwd), shell scripting, sudoers file, logging, error handling.

Project Description: Create a comprehensive Bash script that automates the process of adding, modifying, and deleting users and groups on a Linux system. The script should include robust error handling and log all actions for auditing purposes.

Steps to consider:

Design a menu-driven script that presents options for user/group management.
Implement functions for:
Creating new users (with home directories, shells, and initial passwords).
Deleting users.
Adding users to existing groups.
Removing users from groups.
Creating new groups.
Deleting groups.
Ensure the script prompts for necessary information (username, group name, etc.).
Implement input validation to prevent common errors.
Log all successful and failed operations to a dedicated log file (e.g., /var/log/user_management.log).
Consider how to handle sudo privileges for the script's execution.
Add clear messages to the user about the success or failure of each operation.