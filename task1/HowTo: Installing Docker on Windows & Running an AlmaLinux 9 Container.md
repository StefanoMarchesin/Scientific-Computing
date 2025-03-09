# Installing Docker on Windows & Running an AlmaLinux 9 Container
------------------------------------------

## Introduction
Docker is a powerfull tool that makes it easy to create lightweight, portable, and self-sufficient containers that run your applications or even entire operating systems. This guide will walk you through the process of installing Docker on a Windows machine and running an AlmaLinux 9 container.

>[!NOTE]
>This guide doesn't replace the [official one](https://docs.docker.com/desktop/setup/install/windows-install/). It's just shorter.

## Before installing
Windows Subsistem for Linux 2 (WSL2) is a feature of Windows that allows you to run a Linux environment on your Windows machine without the need to use a virtual machine. 

1. Install or update WSL
   ```powershell
   wsl --install
   ```
   ```powershell
   wsl --update
   ```  
2. Be sure that the active version is 2
   ```powershell
   wsl.exe --set-default-version 2
   ```
3. Restart the pc
   
## Install Docker on Windows
1 Download Docker Desktop
  - Go to the [Docker Desktop page](https://www.docker.com)
  - Click Download for Windows ![image](images/Download_Docker.png)
  - Once downloaded, run the installer

2 Install and Configure
  - Follow the installer prompts.
  - During installation, make sure:
    Use WSL 2 instead of Hyper-V is checked.
  - Complete the installation and restart your PC if prompted.
