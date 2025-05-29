# Bash-scripting-devops
 
This is my first assignment on Devops. 

<strong>TASK</strong>: Linux User and Group Management Script with Logging.

<strong>DIFFICULTY</strong>: Easy

<strong>Skills practiced</strong>: User and group management commands (useradd, usermod, userdel, groupadd, groupdel, passwd), shell scripting, sudoers file, logging, error handling.

<strong>Project Description</strong>: Create a comprehensive Bash script that automates the process of adding, modifying, and deleting users and groups on a Linux system. The script should include robust error handling and log all actions for auditing purposes.
<hr>

<strong>Steps to consider:</strong>

<ul>
<li>Design a menu-driven script that presents options for user/group management.</li>
<li>Implement functions for:</li>
<Li>Creating new users (with home directories, shells, and initial passwords).</li>
<li>Deleting users.</li>
Adding users to existing groups.
Removing users from groups.
Creating new groups.
Deleting groups.
Ensure the script prompts for necessary information (username, group name, etc.).
Implement input validation to prevent common errors.
Log all successful and failed operations to a dedicated log file (e.g., /var/log/user_management.log).
Consider how to handle sudo privileges for the script's execution.
Add clear messages to the user about the success or failure of each operation.
<ul>
<hr>

<strong>SOLUTION</strong>
<hr>