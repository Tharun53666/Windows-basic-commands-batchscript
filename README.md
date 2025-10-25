
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
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\MyLab
```

![image](https://github.com/user-attachments/assets/d67f1d1c-a20e-48a1-bf34-500a8aeaab72)

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

## COMMAND AND OUTPUT
```
cd %userprofile%\Desktop\MyLab
```

![image](https://github.com/user-attachments/assets/f38a1f1a-620a-48d7-adb8-f26be32df0f2)

```
type nul > MyFile.txt
```
![image](https://github.com/user-attachments/assets/f38fe6ae-1221-4b86-8bc7-48664ced23f2)

List the contents of the "MyLab" directory.


## COMMAND AND OUTPUT

```
dir %userprofile%\Desktop\MyLab
```
![image](https://github.com/user-attachments/assets/f1518f44-fb5d-4f9c-bbff-0b4a416492eb)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
![image](https://github.com/user-attachments/assets/a88f3c0d-53c6-475d-a51a-f89475ff9070)

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
![image](https://github.com/user-attachments/assets/5de14ed9-d97f-4764-b983-18b721686cea)

Move the "MyLab" directory to the "Documents" folder.

## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Documents
move MyLab Documents
```
![image](https://github.com/user-attachments/assets/13f4f468-1bcd-4ac1-8625-d7f404dc49e0)


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".

##COMMAND

```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```

![image](https://github.com/user-attachments/assets/f428ae78-9f36-45a6-a072-dc464faf5147)



## OUTPUT


![image](https://github.com/user-attachments/assets/aefb9ddb-bb50-463d-b1f1-54bf7926ac83)


# RESULT:
The commands/batch files are executed successfully.

