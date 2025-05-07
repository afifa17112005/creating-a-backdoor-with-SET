# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
![Screenshot_2025-04-26_11_25_47](https://github.com/user-attachments/assets/a1f0973f-77c0-416b-aebf-64b89ca086f9)

It displays the following menu and select 2 for Website Attack Vectors:
![Screenshot_2025-04-26_11_31_28](https://github.com/user-attachments/assets/f0dedaf3-7c28-408d-8c9b-3a7ebbc67c06)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![Screenshot_2025-04-26_11_31_34](https://github.com/user-attachments/assets/f6b72398-4062-421b-be79-bc7126e6a8bd)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![Screenshot_2025-04-26_11_31_41](https://github.com/user-attachments/assets/0b52f28a-caa3-4316-8b42-03f646476ffa)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![Screenshot_2025-04-26_11_31_45](https://github.com/user-attachments/assets/2c48f0e6-6ac2-45bb-be07-0c3b8be65f03)

It shows the following screen in which the option Google can be selected
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/0193cbac-7713-4059-9246-cd8505b7ec93)

SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/6c606a38-b30b-4aca-8033-e86c60613c76)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/607d462d-fe30-42d1-9382-aa329299af14)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
