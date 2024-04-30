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

# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

```
mkdir %userprofile%\Desktop\MyLab
```

![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/ee0c8654-8653-4428-8ae8-0a3148e8a2c5)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
```
cd %userprofile%\Desktop\MyLab
```

![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/8c2ab80f-54f7-459d-847e-d84126f2eed0)


![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/588aa75d-50b7-4f7d-abee-caa8f85c0377)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
```
dir %userprofile%\Desktop\MyLab
```
![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/35ab4242-477c-49ec-a3cc-e3a15c350726)


## COMMAND AND OUTPUT
Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
```
![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/8e33c4ef-0ea6-4dff-989c-00bde94b02e5)


## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents
```
![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/1404c921-a123-4d61-a4d9-2345521a78b7)



## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!
```



## OUTPUT
![image](https://github.com/bharathganeshsivasankaran/Windows-basic-commands-batchscript/assets/119478098/52baca0d-1fba-486f-b93c-35a81d18d731)





# RESULT:
The commands/batch files are executed successfully.

