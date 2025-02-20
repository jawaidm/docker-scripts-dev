**Required Files:**

Ubuntu 22.04 Can be downloaded here:   
https://ubuntu.com/download/server   

Putty SSH Client can be downloaded here:   
https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/putty.exe?raw=true   
    
   
**Step 1. Install Virtual Box**

https://www.virtualbox.org/wiki/Downloads

**Step 2: Setup Host Adapter**

Click File --> Host Network Manager

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_main_screen.png?raw=true)

a) Click Create and then Select the Adapter ending with #2.  
b) In the bottom box change the adapter IPV4 address to 10.17.0.1.   
c) Click Apply and Close.   

![alt text](https://raw.githubusercontent.com/dbca-wa/docker-scripts-dev/main/windows_vbox/installation/images/file__host_network_adapter.png)


**Step 3: Create New VM**

a) Click NEW Button

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_new_docker_vm.png?raw=true)

**Step 4: Create New VM Naming**

a) Enter under Name "Ubuntu 22.04 (docker)   
b) Drop down should match screenshot   
c) Click Next   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_new_docker_os_vm.png?raw=true)


**Step 5: Create New VM Memory**

a) Select 2048 of Memory (you can choose more if you wish)  
b) Click Next   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_new_docker_memory_vm.png?raw=true)

**Step 6: Create New VM Hard disk file type**

a) Select VDI (VirtualBox Disk Image)
b) Click Next   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_new_docker_storage_type_vm.png?raw=true)

**Step 7: Create New VM Hard disk physical type**

a) Select Dynamically Allocated
b) Click Next   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_new_docker_storage_type2_vm.png?raw=true)


**Step 8: Select Storage Size**

a) Choose approximately 60GB
b) Click Create   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_new_docker_storage_size_vm.png?raw=true)


**Step 9: VM Settings**

a) Select the New VM Created from the left panel   
b) Click Settings from the top bar.   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_vm_settings.png?raw=true)

**Step 10: VM CPU Processor**

a) Select System   
b) Select Processor   
c) Change Processor from 1 to 2 (You can change this more if required)   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_system_processor.png?raw=true)

**Step 11: VM Acceleration**

a) Select System   
b) Select Acceleration   
c) Change Paravirtualization Interface to "KVM"  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_system_acceleration.png?raw=true)


**Step 12: VM Storage Settings**

a) Select Storage   
b) Select Ubuntu 22.04 (docker).vdi
c) Check Solid State Drive 

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_storage_controller_sata.png?raw=true)


**Step 13: VM Select Installation Media**

a) Select Storage   
b) Select Empty under Controller: IDE
c) Select Disk icon on the right and choose the download ubuntu 22.04-live-server image.
d) click ok

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_storage_controller_install_image.png?raw=true)

**Step 14: VM Start**

a) Select "Ubuntu 22.04 (docker)"   
b) Click Start   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%201.png?raw=true)


**Step 15: VM Start**

a) Select "Ubuntu 22.04 (docker)"   
b) Click Start   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%201.png?raw=true)


**Step 16: VM Running**

a) Select (with aarow keys) "Try or Install Ubunutu Server    
b) Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%202.png?raw=true)

**Step 17: VM Language**

a) Select (with aarow keys) "English"   
b) Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%203.png?raw=true)

**Step 18: VM Update Installer**

a) Select "Update to the new installer" - May not get this option if you image is already the latest.  If so skip to next step   
b) Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%204.png?raw=true)

**Step 19: VM Key Board Layout**

a) Both Layout and Variant should be English (US)   
b) Select Done and Press Enter  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%205.png?raw=true)

**Step 20: VM Install Type**

a) X should be selected on Ubuntu Server   
b) Select Done and Press Enter  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%206.png?raw=true)

**Step 21: VM Network**

a) Should see at least one interface configuration   
b) Select Done and Press Enter  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%207.png?raw=true)

**Step 22: VM Proxy**

a) Proxy Address should be empty   
b) Select Done and Press Enter  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%208.png?raw=true)

**Step 23: VM Ubuntu Mirror Location**

a) Mirror address should be an au archive.   
b) Select Done and Press Enter  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%209.png?raw=true)

**Step 24: VM Configure Storage**

a) X should match selection in screenshot    
b) Select Done and Press Enter  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2010.png?raw=true)

**Step 25: VM Configure Storage Space**

a) In the screenshot where is says LVM volume group (make note of that numberm we will need it in the next step)   
b) Using the arrow keys select the number next to mounted at /   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2011.png?raw=true)

**Step 26: VM Configure Storage Space Amount**

a) In the size box enter the amount you wrote down in Step 25.   
b) Select Save and Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2012.png?raw=true)

**Step 27: VM Configure Storage Complete**

a) Select Save and Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2013.png?raw=true)


**Step 28: VM Configure Storage Confirm**

a) Select Continue and Press Enter      

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2014.png?raw=true)


**Step 29: VM Profile Setup**

a) Under Name Enter "Docker"   
b) Under Your server name Enter "Docker"   
c) Under Username Enter "docker"   
d) Under Choose a password Enter "docker"   (you can choose your own password if you wish)   
e) Under Confirm your password Enter "docker"    (you can choose your own password if you wish)   
f) Select Done and Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2015.png?raw=true)

**Step 30: SSH Setup**

a) Add an X next to Install OpenSSH Server   
b) Select Done and Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2016.png?raw=true)

**Step 31: Feature Server Snaps**

a) Nothing to select in here, so select Done and Press Enter   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2017.png?raw=true)

**Step 32: Installing System**

a) Wait for installation to complete go to step 33

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2018.png?raw=true)

**Step 33: Installing System**

a) Once Installation is complete "Reboot Now" will appear under "View Full Log"
b) Select Reboot Now and Press Enter

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2019.png?raw=true)

**Step 34: Installation complete (Login)**

a) Login with the username and password created in step 29   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2020.png?raw=true)
![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2021.png?raw=true)

**Step 35: VM Login**

a) Login with the username and password created in step 29   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2020.png?raw=true)
![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2021.png?raw=true)

**Step 36: Edit Network Config**

a) Login into the system as root "sudo su"   
b) edit file "vi /etc/netplan/00-installer-config.yaml"   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2022.png?raw=true)

**Step 37: Update Network Config**

a) At line 6 we need to insert 3 new lines with correct tabing (see screenshot)
```
    enp0s8:   
       dhcp4: false    
       addresses: [10.17.0.10/24]    
```   
b) Save and exit.   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2023.png?raw=true)
![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2024.png?raw=true)

**Step 38: VM Reboot**

a) Enter "Reboot" and press Enter

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2025.png?raw=true)

**Step 39: SSH to VM (Putty)**

a) Open Putty (Putty can be downloaded from within this repo)   
b) Enter "10.17.0.10" into Host Name , Saved Session and click Save   
c) Double Click 10.17.0.10 at reference Point 4 in screensheet.   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2026.png?raw=true)

**Step 40: SSH to VM (Login)**

a) At prompt enter login details that were created at step 29 and login.    When entering the password you will not see asterisks or characters appear.   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2027.png?raw=true)


**Step 41: Install Docker**

a) Enter the following command into the putty screen and press enter. You should be able to copy and paste the following command (putty accept right mouse click for paste)
```
curl https://raw.githubusercontent.com/dbca-wa/docker-scripts-dev/main/windows_vbox/installation/docker-install.sh | bash
```
b) you will be ask for the password created at step 29. Please enter the password and press enter (asterisk or characters will not appear while entering the password)

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2028.png?raw=true)

**Step 42: Check Docker Installation is Complete**

a) enter at the prompt "docker ps" and press enter to conifrm docker is installed correctly.
b) You should see a similar response to the screenshot.

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2029.png?raw=true)

**Step 43: GIT Check out docker system run scripts**  

a) Run the follow command to pull a copy the dbca docker scripts:  (this should be run while in your home directory)   
```
git clone https://github.com/dbca-wa/docker-scripts-dev.git
```

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2030.png?raw=true)

**Step 44: GIT Check out docker system run scripts**   

a) Change Directory "cd docker-scripts-dev/windows_vbox"   
b) run command "mkdir env"   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2031.png?raw=true)

**Step 45: Start Postgres Server**  

a) Run "./postgres_docker_load.sh" (you might need to 'chmod 755 postgres_docker_load.sh' this file)   
b) Run "docker ps" to check the postgres container is running (see screenshot)   
c) Run "../tools/connect_postgres.sh" (this will allow you to connect into the container) - your prompt should change  

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2032.png?raw=true)
![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2033.png?raw=true)

**Step 46: Start Postgres Server**   

a) Run "./create-new-postgres.sh" (This will create your postgres database inside the container,  never run this if you have a database setup as it will wipe your databases)  
b) Run "exit" So you can leave the container and go back to docker@dockerdev:~ prompt

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2034.png?raw=true)

**Step 47: Start Webdav Server**   

a) Run "./webdav_docker_load.sh" (this will allow you to share files from windows into the containers)   
b) Run "docker ps" to check the webdav container is running (see screenshot)   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2034.png?raw=true)

**Step 48: Check Webdav Server**   

a) Open your browser (chrome,firefox) and enter this url "http://10.17.0.10:6999/webdav"   
b) You should receive a simliar page to the screenshot to confirm the webdav server is working.   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2036.png?raw=true)

**Step 49: Create share drive in windows**   

a) In Windows File Manager right click "This PC" and click "Map network drive"   
b) Select Drive (Maybe M:)   
c) In Folder type in "http://10.17.0.10/webdav"   
d) Click finish   
e) You should now a map drive to windows that will let you share files between your container and windows.   

![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2037.png?raw=true)
![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2038.png?raw=true)
![alt text](https://github.com/dbca-wa/docker-scripts-dev/blob/main/windows_vbox/installation/images/vbox_start_ubuntu_installation_step%2039.png?raw=true)

**Completed**
