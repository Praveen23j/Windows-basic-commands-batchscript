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

<img width="755" height="261" alt="image" src="https://github.com/user-attachments/assets/2c7bdc05-5220-4860-9d6a-3ca9f74dd65b" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1006" height="358" alt="image" src="https://github.com/user-attachments/assets/66562e72-36da-40f8-a1d2-af2c35470ab0" />



Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="965" height="423" alt="image" src="https://github.com/user-attachments/assets/0a3f5e98-b0a5-4673-9228-15f2fc2eba77" />



Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="1001" height="117" alt="image" src="https://github.com/user-attachments/assets/cdcb3aab-2b1e-44ee-8315-2833177c34ed" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="1002" height="153" alt="image" src="https://github.com/user-attachments/assets/7621cdea-cdc4-448a-a59a-6a673c1fb8d8" />


Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="922" height="261" alt="image" src="https://github.com/user-attachments/assets/06e131ab-5906-446e-a8fc-8a2c8eb9c752" />


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="809" height="872" alt="image" src="https://github.com/user-attachments/assets/52cf6178-1524-41cb-baed-70c43ccbd552" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="802" height="903" alt="image" src="https://github.com/user-attachments/assets/c9457bf2-55c3-4cc1-abb8-ab54f2051e6f" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="932" height="217" alt="image" src="https://github.com/user-attachments/assets/0f66efa0-d871-4c46-b57b-5be29ea30a23" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="855" height="106" alt="image" src="https://github.com/user-attachments/assets/61c006b0-1a6e-4c1b-86d2-7465f7fa290c" />




Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="880" height="294" alt="image" src="https://github.com/user-attachments/assets/f5e971c4-3a62-4f16-9fbf-fe19685a7219" />





Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="852" height="241" alt="image" src="https://github.com/user-attachments/assets/faaf422f-8e40-4954-bcc9-7e71587bef6a" />





Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="849" height="106" alt="image" src="https://github.com/user-attachments/assets/1c098843-0914-47fc-bb92-639fb5cdef73" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="849" height="546" alt="image" src="https://github.com/user-attachments/assets/34db0268-5412-4f26-92af-004996768f36" />



# RESULT:
The commands/batch files are executed successfully.

