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
      <li>Adding users to existing groups.</li>
      <li>Removing users from groups.</li>
      <li>Creating new groups.</li>
      <li>Deleting groups.</li>
      <li>Ensure the script prompts for necessary information (username, group name, etc.).</li>
      <li>Implement input validation to prevent common errors.</li>
      <li>Log all successful and failed operations to a dedicated log file (e.g., /var/log/user_management.log).</li>
      <li>Consider how to handle sudo privileges for the script's execution.</li>
      <li>Add clear messages to the user about the success or failure of each operation.</li>
  <ul>

#  SOLUTION
 <strong>The</strong> first thing that needs to be done is to first create your file. This file has to be a bash file that will end with <em>.sh</em>. The name of this file is <strong>users.sh</strong>

<strong>STEP 1:</strong>
User and group management needs administrative access so the script written must first chack that. 
<img src ="images/image1.jpg">

<strong>STEP 2:</strong>
Create a log file to keep track of what happens.
<img src ="images/image2.jpg">

<strong>STEP 3:</strong>
Write out the function to create a new user 
<img src ="images/image3.jpg">

<strong>STEP 4:</strong>
Repeat the same logic for other actions.
<img src ="images/image4.jpg">

<strong>STEP 5:</strong>
Build a menu for easy user access.
<img src ="images/image5.jpg">

<hr>
<strong>END RESULT</strong>

