# finalCapstone
# Contents
A) Projects description
B) Usage of code
C) Installation Notes

# A) Projects description: This repository has two tasks T17 and T18. The description of which can be found as follows:

Task 17: The pyhton code is for Task Management System (TMS) application. It allows users to register, add tasks, view tasks, generate reports, display statistics, and exit the program. The application stores user information in a "user.txt" file and task information in a "tasks.txt" file. Overall, the code provides basic functionality for managing tasks and users.
Running the code: 
1. Use the following username and password to access the admin rights 
  username: admin
  password: password
2. Ensure you open the whole folder for this task in VS Code otherwise the program will look in your root directory for the text files.
Credits: Sample code template is provided by HperionDev 

Task 18: 

# B) Usage
Task 17: Breakdown of the code structure and functionality.
1. The code imports the necessary libraries and defines the current date format. 
2. The code if refectored to use functions which are defined as follows:
   
reg_user(): Allows a new user to register by providing a unique username and password. The user information is stored in the "user.txt" file.

add_task(): Allows a user to add a new task by providing details such as the assigned username, task title, description, and due date. The task information is stored in the "tasks.txt" file.

view_all(): Reads task information from the "tasks.txt" file and prints all tasks in a specific format.

view_mine(): Reads task information from the "tasks.txt" file and prints tasks assigned to the current user in a specific format.

generate_reports():  function is defined to generate task and user overview reports. The reports are written to "task_overview.txt" and "user_overview.txt" files.

display_stats(): function is defined to display statistics about the number of users and tasks. This function is only accessible to the admin user.

3. The code checks for the existence of the "tasks.txt" and "user.txt" files. If they don't exist, they are created with default content.
4. The "tasks.txt" file is read to populate the task_list with task information.
5. The "user.txt" file is read to populate the username_password dictionary with user information.
6. The code prompts for username and password to login. If the provided credentials are correct, the user is logged in. Otherwise, appropriate error messages are displayed.
7. After successful login, the program presents a menu of options to the user. The user can choose to register a user, add a task, view all tasks, view their own tasks, generate reports, display statistics, or exit the program.
Based on the user's selection, the corresponding function is called.
8. If an invalid option is chosen, an error message is displayed.

Task 18: 


# C) Installation notes: How to download the code to local PC
1. Open VS Code on your local PC.
2. Open the Command Palette in VS Code. Can use the shortcut Ctrl+Shift+P (Windows/Linux) or Cmd+Shift+P (Mac)
3. Clone a Repository -> In the Command Palette, type "Git: Clone" and select the option "Git: Clone" that appears. 
4. Enter the URL: https://github.com/pbkvarma/finalCapstone.git of the GitHub repository you want to download into the input box.
5. Choose a  local existing directory or create a new one to download the repository.
6. Once cloned open the cloned repository choose "Yes" to open the repository in a new window.
7. The repository is now downloaded, and you can start working with the code. 
8. To get the repository with the latest changes from GitHub use PULL command request in the terminal.




