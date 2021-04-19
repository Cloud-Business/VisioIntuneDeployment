# Visio Intune Deployment
Package for deploying Microsoft Intune via Microsoft Intune using built in MDT component

Deploy app via Intune

Select a Windows app (Win32) 

Select the .intune file for the Visio install

App Install Details
------------------------
Name: Microsoft Visio
Description: Install Microsoft Visio alongside existed M365 suite installation. Install requires M365 apps to be closed.
Publisher: Microsoft
Show this as featured app in the Company Portal:No
Logo: Upload logo PNG from root folder

Program Details
------------------------
Install: .\ServiceUI.exe -Process:explorer.exe Deploy-Application.exe
Uninstall: .\ServiceUI.exe -Process:explorer.exe Deploy-Application.exe -DeploymentType Uninstall

Detection Details
------------------------
Detection Path
C:\Program Files\Microsoft Office\root\Office16

Detection File
visio.exe

Operating System Minimum
------------------------
Operating system architecture	64-bit
Minimum operating system 	Windows 10 1607
