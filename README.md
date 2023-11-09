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

## EXECUTION STEPS AND ITS OUTPUT :

Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/f40c07e5-b65c-4a6e-9c7d-5de94262e1cb)


 It displays the following menu and select 2 for Website Attack Vectors:


 ![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/4a42b097-2032-475d-936c-11b584be0eca)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:


![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/778edbcb-892e-47e2-a20e-ca580debc47d)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:



![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/dda35133-dc0d-4ad1-8a55-7b0574b5fb6d)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:



![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/d618cb1a-7999-4302-9040-2cd040ef2650)


It shows the following screen in which the option Google can be selected:



![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/bfa3d4bc-d38b-4935-9049-ad3b20be1aa9)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:


![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/c906e696-c26c-496e-af0a-cda30a01a3d8)

SET logs the information in the xml file under /root/.set directory:


![image](https://github.com/priya672003/creating-a-backdoor-with-SET/assets/81132849/5c39bd6d-eb6f-4776-8f02-f5a438b4fc15)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
