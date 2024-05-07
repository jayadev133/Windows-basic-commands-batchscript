# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 
##PROGRAM:
```
DEVELOPED BY:P.ADITYA NAGA SAI
REGISTER BY:212223110036

```

# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt
```

## OUTPUT: 
![image](https://github.com/Nagasaichowdary/Windows-basic-commands-batchscript/assets/155174528/6d0e51e8-8e6a-4973-a050-bdfb5ad8075a)

##COMMAND:
List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```
##OUTPUT:

![image](https://github.com/Nagasaichowdary/Windows-basic-commands-batchscript/assets/155174528/99d6c08e-4b59-42fb-ab54-e6a4a22c3a6d)

## COMMAND

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup
```
##OUTPUT:
![image](https://github.com/Nagasaichowdary/Windows-basic-commands-batchscript/assets/155174528/95aa5fef-614c-4c22-9beb-8f75e8d0da04)

## COMMAND AND OUTPUT


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
```

## OUTPUT
![image](https://github.com/jayadev133/Windows-basic-commands-batchscript/assets/150319465/9329856b-286b-4f8b-be2b-a00fe55c0e8b)
##COMMAND:
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
```
##OUTPUT:
![image](https://github.com/jayadev133/Windows-basic-commands-batchscript/assets/150319465/6eeef4a6-7d82-4a16-bc73-cc2f237a5445)


# RESULT:
The commands/batch files are executed successfully.
