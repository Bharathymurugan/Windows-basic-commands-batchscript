# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="782" height="102" alt="image" src="https://github.com/user-attachments/assets/b9e93695-9931-42f2-9dee-5c5d7eb98a51" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="812" height="51" alt="image" src="https://github.com/user-attachments/assets/7e215aec-eb24-4d7c-ac7d-1a1eab3f88c0" />


Create the file Rose.txt

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="957" height="257" alt="image" src="https://github.com/user-attachments/assets/5cd64684-015a-41e1-834a-eb78bc42f0e6" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="890" height="115" alt="image" src="https://github.com/user-attachments/assets/2857df4e-f9a6-4d9b-b171-173357f9cf1f" />
Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="825" height="48" alt="image" src="https://github.com/user-attachments/assets/dda8ac62-aaf8-4cd0-873f-8d1871a2e078" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="786" height="221" alt="image" src="https://github.com/user-attachments/assets/a386eb11-80e4-433b-b19d-ffc4ea7b4e1b" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="718" height="125" alt="image" src="https://github.com/user-attachments/assets/00edb1dc-af46-404f-b09d-1dc1f2e0aad3" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="866" height="190" alt="image" src="https://github.com/user-attachments/assets/50059e60-3c6a-469b-9c68-23806734ec2e" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="762" height="195" alt="image" src="https://github.com/user-attachments/assets/0e963d59-05ad-4c82-a97d-2d823b9ab16d" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="740" height="225" alt="image" src="https://github.com/user-attachments/assets/5b111450-4294-44f8-89ae-1f2626de9462" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="747" height="182" alt="image" src="https://github.com/user-attachments/assets/6ebb9554-ff2d-4baf-94e7-63de1c9e0d39" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="872" height="90" alt="image" src="https://github.com/user-attachments/assets/029704c0-7c94-438b-a7c5-dcd1e45859b8" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="767" height="686" alt="image" src="https://github.com/user-attachments/assets/502351eb-1665-4926-8ae9-43eaf1c22f27" />



# RESULT:
The commands/batch files are executed successfully.

