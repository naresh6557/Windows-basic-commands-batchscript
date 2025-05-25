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

```
mkdir %userprofile%\Desktop\MyLab
```
![Screenshot 2025-05-20 213851](https://github.com/user-attachments/assets/67d57631-ab66-4d22-a146-8115a2e3c0f4)


## COMMAND AND OUTPUT

```
cd %userprofile%\Desktop\MyLab
```

![Screenshot 2025-05-20 213859](https://github.com/user-attachments/assets/6a1baf0b-2a0f-4dc2-b4c0-6da8d2fe315d)

```
type nul > MyFile.txt
```

![Screenshot 2025-05-20 213908](https://github.com/user-attachments/assets/0d23b56d-83f1-4e68-adb4-ae3070678ba0)


## COMMAND AND OUTPUT
```
dir %userprofile%\Desktop\MyLab
```
![Screenshot 2025-05-20 213915](https://github.com/user-attachments/assets/0611f82e-d1ac-4b1d-9a41-731ffdcb67f9)


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
![Screenshot 2025-05-20 213922](https://github.com/user-attachments/assets/00649aa1-e258-434c-bdc2-0ce6d179002d)


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Backup
```
![Screenshot 2025-05-20 213930](https://github.com/user-attachments/assets/99132b9c-85df-4396-8b03-7a0b2645ef0a)


## COMMAND AND OUTPUT
```
mkdir %userprofile%\Desktop\Documents
move MyLab Documents
```
![Screenshot 2025-05-20 213939](https://github.com/user-attachments/assets/6f9b1899-fd65-445c-9c2e-ffba94e00cfe)


## COMMAND AND OUTPUT

List out all the associated file extensions 

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
![Screenshot 2025-05-20 213947](https://github.com/user-attachments/assets/46d023d2-940c-4839-a208-3eefc012d8df)

## OUTPUT
```
  @echo off
  mkdir %userprofile%\Desktop\DocBackup
  copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
  del %userprofile%\Documents\*.docx
  echo Backup and deletion completed successfully!
```

![Screenshot 2025-05-20 214011](https://github.com/user-attachments/assets/28aa0f55-9265-4f30-a30d-76685778ae97)


# RESULT:
The commands/batch files are executed successfully.

