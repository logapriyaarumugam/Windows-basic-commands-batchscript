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

Remove the directory "my-folder"
<img width="388" height="130" alt="image" src="https://github.com/user-attachments/assets/234c0c34-a7b3-46ea-a87f-ed5260796a4a" />

## COMMAND AND OUTPUT
Create the file Rose.txt
<img width="617" height="532" alt="image" src="https://github.com/user-attachments/assets/e11ea8b5-33de-4e7b-a38c-054d7f42e8cf" />

## COMMAND AND OUTPUT
Create the file hello.txt using echo and redirection
<img width="536" height="115" alt="image" src="https://github.com/user-attachments/assets/8047c8a1-36a1-4f24-955e-77ce42519260" />

## COMMAND AND OUTPUT
Copy the file hello.txt into the file hello1.txt
<img width="620" height="131" alt="image" src="https://github.com/user-attachments/assets/37024c8c-d3bb-4028-9d8f-a548d61c673b" />

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="473" height="62" alt="image" src="https://github.com/user-attachments/assets/743fa308-8e1f-4ced-a94d-87d3dde0146a" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="637" height="260" alt="image" src="https://github.com/user-attachments/assets/2d83d5a1-1ae2-4812-9f78-06737fac4c50" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="653" height="945" alt="Screenshot 2026-09-10 002155" src="https://github.com/user-attachments/assets/a4b1ba82-d36c-4664-bbf7-1d2239104527" />

## COMMAND AND OUTPUT
Compare the file hello.txt and rose.txt
<img width="718" height="840" alt="Screenshot 2026-09-10 002303" src="https://github.com/user-attachments/assets/99906889-d9a4-4653-a1cb-e73bec7b79ca" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="772" height="786" alt="Screenshot 2026-09-10 002620" src="https://github.com/user-attachments/assets/47619bb8-936d-4a4e-97d0-c3680999e29f" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="640" height="396" alt="Screenshot 2026-09-10 002739" src="https://github.com/user-attachments/assets/125cc39e-83a9-4e06-841d-703ff44073d7" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="507" height="237" alt="Screenshot 2026-09-10 002820" src="https://github.com/user-attachments/assets/65c989f9-2f5c-4599-bec6-4e0b62d4b5d2" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="527" height="97" alt="Screenshot 2026-09-10 002858" src="https://github.com/user-attachments/assets/2733edc0-2e9d-4c13-80b6-fa48bdf34bfd" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="465" height="492" alt="Screenshot 2026-09-10 002956" src="https://github.com/user-attachments/assets/7156edfb-e77d-4ea2-a1de-2d5254c797f6" />



# RESULT:
The commands/batch files are executed successfully.

