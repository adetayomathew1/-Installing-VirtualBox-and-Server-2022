<H1>Overview: Lab 1 Installing VirtualBox and Server 2022</H1>

Welcome to the first lab of my home lab series! This section of my home lab documentation focuses on the process of **installing VirtualBox** and setting up a **Windows Server 2022** virtual machine within the VirtualBox environment. It outlines the steps for downloading and installing **VirtualBox**, followed by the creation of a virtual machine to host **Windows Server 2022**. The project also covers the configuration of basic server settings and prepares the server for further roles, such as Active Directory and domain controller setup. This task serves as the foundation for building a virtualized lab environment that mimics real-world IT infrastructure, ideal for practicing administrative tasks and learning server management techniques.

<H2>Objectives</H2>

This repository documents a comprehensive home lab project focused on installing and configuring VirtualBox and Windows Server 2022. The key objectives include:

- Demonstrating the setup and installation process of VirtualBox as a virtualization platform.
- Installing and configuring Windows Server 2022 in a virtualized environment.
- Creating a foundation for further experiments involving Active Directory, system administration, and IT operations.



<H2>Documentation</H2>

In this documentation, I will outline the initial steps of setting up my Active Directory home lab. This includes downloading and preparing the essential tools: VirtualBox and Windows Server 2022.

To start, we’ll download VirtualBox from the official website at https://www.virtualbox.org/wiki/Downloads. Since I’m using a Windows PC, I will be selecting the version for Windows hosts.



1. <p align="center">
   <img src="https://i.imgur.com/AqLqP6W.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

Next, we’ll download Windows Server 2022 from the official Microsoft Evaluation Center at https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022.

2. <p align="center">
   <img src="https://i.imgur.com/eY4Dajh.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

To access the free trial, you’ll need to provide your information during the registration process. The trial period lasts for 180 days.

3. <p align="center">
   <img src="https://i.imgur.com/K58G1Zo.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

After filling our information, we can finally download the ISO which will be the 64-bit edition (English). 

4. <p align="center">
   <img src="https://i.imgur.com/9x6LZ39.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

Finally our ISO download should appear in our downloads folder. 

5. <p align="center">
   <img src="https://i.imgur.com/30c16bl.png" height="100%" width="100%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

After everything has finished downloading, we can launch VirtualBox and begin configuring the settings for Windows Server 2022. Once VirtualBox is open, navigate to the "Machine" tab at the top and select "New" to create a new virtual machine.

6. <p align="center">
   <img src="https://i.imgur.com/FxItaBK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

First, we’ll name our virtual machine "Windows Server 2022 Lab." Next, we’ll locate the ISO image in our Downloads folder. To do this, click the dropdown menu under "ISO Image" and select "Other." From there, we can browse to the Downloads folder and select the Windows Server ISO.

7. <p align="center">
   <img src="https://i.imgur.com/XBXdsca.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

8. <p align="center">
   <img src="https://i.imgur.com/a200rRl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
   <br />


9. <p align="center">
   <img src="https://i.imgur.com/mfGHPO8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <br />
   <br />

Next, click on "Skip Unattended Installation." Then, proceed to configure the hardware settings for the virtual machine.


10. <p align="center">
    <img src="https://i.imgur.com/arMmGDo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

By default, the base memory is set to 2048 MB, which should be sufficient for running the virtual machine. However, since our computer has 32 GB of RAM, we can allocate around 6 GB (or 6081 MB) for our virtual machine home lab. To check how much RAM your PC has, you can either search for "About your PC" or open Task Manager and navigate to the "Performance" tab, where the total RAM will be displayed.

11. <p align="center">
    <img src="https://i.imgur.com/XPKT8Od.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />



12. <p align="center">
    <img src="https://i.imgur.com/vDjv9av.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

For the “Hard disk” configurations everything should be good, just make sure we have “Create a Virtual Hard Disk Now” then click “Finish”. 

13. <p align="center">
    <img src="https://i.imgur.com/NQXAbMz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

Now, we’ll boot up the virtual machine by clicking the "Start" button. A prompt for the Microsoft Server Operating System Setup will appear. Click "Next," then select "Install Now" to begin the installation process.

14. <p align="center">
    <img src="https://i.imgur.com/lxojjhr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />


15. <p align="center">
    <img src="https://i.imgur.com/G4obXiC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

In the operating system selection screen, choose "Windows Server 2022 Standard Evaluation (Desktop Experience)," then click "Next" to continue.

16. <p align="center">
    <img src="https://i.imgur.com/dKzoj75.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

Accept the terms and click "Next." In the next step, when prompted to choose the type of installation, select "Custom" to proceed.

17. <p align="center">
    <img src="https://i.imgur.com/jtsl1SH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />


18. <p align="center">
    <img src="https://i.imgur.com/U8758Tl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

Click "Next," and the installation of Windows Server will begin.

19. <p align="center">
    <img src="https://i.imgur.com/cTvNebb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

20. <p align="center">
    <img src="https://i.imgur.com/JOB6AEb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

Create a password for our account “Administrator”.

21. <p align="center">
    <img src="https://i.imgur.com/BVNQbcT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

Click on "Input" and select "Insert Ctrl + Alt + Del" to bring up the login screen. After entering your password, you can log into your Windows Server 2022 account as the administrator.

22. <p align="center">
    <img src="https://i.imgur.com/S6UqGhP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />

23. <p align="center">
    <img src="https://i.imgur.com/2ezAwcQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
    <br />
    <br />


Congratulations we have now successfully installed Windows Server 2022 and Virtual Box!

 👉 [Next Lab 2 : Renaming Windows Server 2022 and Installing Active Directory](https://github.com/Simokid/Renaming-Server-2022-and-Installing-Active-Directory/tree/main)


















