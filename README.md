<!-- hide -->
 # VIRTUAL MACHINE CREATION IN LINUX
 ### Name   : V YASHWANTH RAJA DURAI 
 ### REG_NO : 212222040184
## Installing kali linux on virtual machine




Installing Kali Linux on a virtual machine is an excellent way to explore and use this powerful security tool without risking your main operating system. This approach provides a secure and flexible environment that is ideal for both learning and professional applications. In this practice, we will learn how to install one.


### Requirements
* Download VirtualBox from [Downloads](https://www.virtualbox.org/wiki/Downloads).
* Download Kali Linux from Kali Linux [Downloads](https://www.kali.org/get-kali/#kali-platforms).
## AIM
To Install Virtualbox / VMware Workstation with different flavours of linux.
## PROBLEM STATEMENT
This experiment involves setting up a virtual machine with CentOS, a popular Linux distribution. This setup allows users to practice Linux commands, test applications, and develop software in a virtualized environment without affecting the host system.


## ALGORITHM /📝 Instructions
### Step 1: Installing VirtualBox
VirtualBox is a free and open-source virtualization tool that allows users to run multiple operating systems simultaneously on their computer.

 - [ ] Run the downloaded installer and follow the installation wizard instructions.
 - [ ] Once installed, open VirtualBox.

 ![installing virtualBox](https://raw.githubusercontent.com/breatheco-de/installing-kali-linux-on-virtual-machine/main/assets/virtualbox-img.png)


### Step 2: Downloading Kali Linux Virtual Machine
 * Download from Kali Linux [Downloads](https://www.kali.org/get-kali/#kali-platforms).

> 💡 NOTE: You can download an ISO image for a fresh installation or a pre-configured image for VirtualBox (OVA/VBOX). In this practice, we'll use the VBOX image.

![download 1](https://raw.githubusercontent.com/breatheco-de/installing-kali-linux-on-virtual-machine/main/assets/get-kali-linux.png)

- [ ] In the virtual machines section, select the VirtualBox version and download the VBOX file (typically comes as a compressed file).

![download 2](https://raw.githubusercontent.com/breatheco-de/installing-kali-linux-on-virtual-machine/main/assets/get-kali-for-vb.png)

- [ ] If the VBOX file is compressed, unzip it using a tool like 7-Zip, WinRAR, or your OS's built-in decompressor.

### Step 3: Creating the Virtual Machine

 - [ ] Go to the folder where you extracted the Kali Linux download and double-click the `vbox` file. This will start your Kali machine with all configurations ready: machine name, operating system type, CPU, etc.

> 💡 IMPORTANT: If you are doing this with an OVA file, you should:

* Go to the File option in VirtualBox -> `Import Appliance...`
* In the window that opens, click on `Choose virtual appliance file...` and select the OVA file of Kali Linux you downloaded.
* In the next window, you can review and adjust the virtual machine settings (e.g., memory allocation, number of CPUs, etc.). At least 2 GB (2048 MB) is recommended, but 4 GB (4096 MB) or more would be ideal for better performance.

![config kali](https://raw.githubusercontent.com/breatheco-de/installing-kali-linux-on-virtual-machine/main/assets/preferences-vm-ova.png)

* Once you are satisfied with the settings, click Import/Finish.

### Step 4: Starting the Virtual Machine

- [ ] Select the Kali Linux virtual machine and click "Start." The VM will boot up, and you'll see the Kali Linux boot screen.
- [ ] Use the default credentials to log in:
     Username: kali
     Password: kali

### Step 5: System Update (Recommended)
Open a terminal and run the following commands to update the system:

```sh
sudo apt update
sudo apt upgrade -y
```

All Set!
Now you can start using Kali Linux on your virtual machine.
### -----------------------------------------------------------------------------------------------------
### Run some of the commands to check if your kali linux on virtual machine is working properly or not.

## COMMANDS

### Hostname Setting :
    hostname
### IP Address Setting :
    nmtui
    ip a
### Date , System & OS Information :
    date 
    cal
### Basic File Management :
    pwd
    cd
    mkdir
    touch
### Basic File management – File Editor :
    Cat <file name> - Help us to shown the content from the file.

    Cat> <file name> - Help us to write or overwrite from the file.

    Cat>> <file name> - Help us to add on new lines from existing file content.


## OUTPUT :

![1](img/Screenshot_2025-02-26_03_16_59.png)


![2](img/Screenshot_2025-02-26_03_22_33.png)

 
 
## RESULT :
Successfully installed Kali Linux on a virtual machine using VMware, providing a fully functional Kali Linux environment for testing and development.
 


