# Virtual-Home-Lab
The process I went through to install a Virtual home lab through Virtual Box
# Objective
Setting up a home lab to learn linux. Also just incase i want to start malware analysis having  a safe environment to develope and test theory.

# Skills Learned

- Setting up windows OS
- Setting kali OS
- How to run VirtualBox
- How to operate in both windows and kali 


# Tools Used

- VirtualBox
- Kali Linux
- Windows 10
- Splunk

# Steps
- Download vitualbox
- Go to the windows page and download the 64 bit versions for the windows media installer

![image](https://github.com/user-attachments/assets/8f465146-e093-46c6-82c7-3cc155428acb)

- Went in to virtualbox clicked add and found the file in my file directory to start the download
- Downloading windows 10 OS on to VirtualBox 

![image](https://github.com/user-attachments/assets/9a84f4c5-6d83-4e29-a08f-2292572d028f)

- Microsoft windows 10 is downloaded and running on VirtualBox

![image](https://github.com/user-attachments/assets/a39c4eff-0775-4c3e-a069-1a2273d35865)

- Went to kali.org to download an open source pre-built virtual machine for kali linux 

![image](https://github.com/user-attachments/assets/fcdc7284-0780-4d2b-b13c-eb01e433fbf2)

- Extracted kali pre build from the 7zip folder with winrar

  ![image](https://github.com/user-attachments/assets/060d8af2-a6da-44a4-8f51-102b8cd676bf)

- Make sure to double click the one with the .vbox file extension since it was made specifically for virtual box

  ![image](https://github.com/user-attachments/assets/c38c1f23-79ab-4142-a0e2-f4cd3b7d1aea)

- Time to settup kali linux through virtual lab
- Click on the kali linux demo and then click the start tab

  ![image](https://github.com/user-attachments/assets/e836caf2-781b-4070-b5e7-1c33011aeeb0)

- The default username is kali
- the default password is kali
- Now kali linux is up and running

  ![image](https://github.com/user-attachments/assets/2bf50072-cfea-4ba6-ad10-b841a170fcb6)

- Click on settings and go down to network
- Make sure your on and internal network other wise if you test malware it could potentially infect your host computer

  ![image](https://github.com/user-attachments/assets/1a2f8078-77a4-4c7f-8438-b399a139ebd0)

  ![image](https://github.com/user-attachments/assets/cdda5628-5cbb-4914-bf98-df63496e2f65)

  - Assign new ip addresses for both VM's
  - Run windows vm click on the network and bring up network options
  - Click on change adapter options

    ![image](https://github.com/user-attachments/assets/e589eebc-2665-422f-9a9c-864bf5b31f68)

  - Right click on ethernet and bring up properties

  ![image](https://github.com/user-attachments/assets/2b7a5b7b-e3ca-40e4-824c-e106085a836a)


  -  Click on internet version 4 and the click on properties again

    ![image](https://github.com/user-attachments/assets/6ab7cd01-aaf3-4943-b7ad-f67e838585c9)

 - click on use the following IP address
 - and assign your ip address and sub net address

   ![image](https://github.com/user-attachments/assets/a832f07a-8481-4a2a-bca3-d3992d5312d7)

- checking command prompt to see if my ip address is working
- Open command prompt and type in ipconfig to check if your ip address is set

  ![image](https://github.com/user-attachments/assets/49b454d5-f962-4765-9851-fb39e4e824cb)

- Open the kali linux VM 
- Right click on the internet option in the upper right hand corner
- Click on wireless connection
- Click the gear icon at the bottom left corner

  ![image](https://github.com/user-attachments/assets/1f6eac7c-c00a-43c5-ac90-a56f318b62ca)

- Click on the ipv4 settings

  ![image](https://github.com/user-attachments/assets/c1bc0234-bddb-4a1f-996a-76d88043f4df)

 - Change the method to manual click on add
 - Change your ip address and your Netmask then click save

   ![image](https://github.com/user-attachments/assets/3984d38a-1636-437d-a20e-7b3a4a676ccb)


- Pull up the terminal and type in ifconfig to check if your ip address is settup
- I changed mine to 192.168.20.25

  ![image](https://github.com/user-attachments/assets/ead60235-8842-41c2-906b-8a0c63354528)

- Checking to see if i can ping my windows VM from my kali VM

- Windows system unreachable due to firewall interferance

  ![image](https://github.com/user-attachments/assets/89a1e478-21d9-4c06-a404-fd09df77a85e)

- Testing ping from my windows VM to kali linux

- Having issues connecting to kali linux as well will be testing more to fix these issues

  ![image](https://github.com/user-attachments/assets/27528cd0-3f3e-4e4e-9d86-c277da644e3f)

- Update make sure to change the network for every single one of you VM's once my kali linux VM was changed to internal internet the issuse was resolved and I could connect.

  ![image](https://github.com/user-attachments/assets/02448b62-d354-4eeb-90df-79e0d02b91eb)


- Once this is done you will have and windows and kali linux VM settup with static ip address that are not connected to your host computer

  # Adding software

  -


    


  

