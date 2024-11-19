# SMSS_Installation

## Objective
[Brief Objective]


The objective of the project is to install and configure SQL Management Studio 2.0.2 on Windows 11 using PowerShell. This repository aims to simplify the setup process, ensuring consistency, accuracy, and efficiency for users who need to quickly deploy SQL Management Studio in their development or production environments.

[Tools Used]

-Powershell Terminal

## Steps

Right click your start button and run PowerShell Terminal as an Administrator

 ![image](https://github.com/user-attachments/assets/5640d3a3-3967-4fa9-94ec-18526cf37246)


Open PowerShell and type `winget search sql`. 

WinGet is a command-line tool that allows users to discover, install, upgrade, remove, and configure applications on Windows 10, Windows 11, and Windows Server 2025 systems.


![image](https://github.com/user-attachments/assets/2ec3e924-e83e-4ab2-b026-4c0431456939)

 
A list of installable SQL applications will appear. Type `winget install Microsoft.SQLServerManagementStudio` and press Enter. This will install Microsoft SQL Server Management Studio version 2.0.2.


![image](https://github.com/user-attachments/assets/81686926-53f1-4150-89e4-17a1530e498a)
![image](https://github.com/user-attachments/assets/3d8f33f4-a6e7-4077-b413-64ea64ecf6c6)

 
Type `winget install Microsoft.SQLServer.2019.Express` and press Enter. This will install Microsoft SQL Server 2019 Express and provide the server name and login information. 


![image](https://github.com/user-attachments/assets/f4a3e348-e945-4f1e-a766-70ac47819c46)
![image](https://github.com/user-attachments/assets/1d693dff-fcbf-4dc6-a541-6849a5da5d1b)


 
Search for SQL Server Management Studio, launch the application, and run it as an Administrator.


![image](https://github.com/user-attachments/assets/a8c5a916-c947-41f1-8bd0-5a2685e1d2f7)
![image](https://github.com/user-attachments/assets/0ba1838c-b889-4f6b-8088-cdb2c8eb0e9f)


  
Enter the server and login information provided into SQL Server Management Studio to complete the basic configuration.

 
![image](https://github.com/user-attachments/assets/4e3f7c4b-9c87-4841-b50e-9217955c47a1)
![image](https://github.com/user-attachments/assets/3be333b8-8ccd-4e02-b9b9-d3dc4ce0dc1e)

 
