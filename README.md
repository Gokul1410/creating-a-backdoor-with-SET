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
## OUTPUT

<img width="664" height="1112" alt="Screenshot 2026-08-25 142659" src="https://github.com/user-attachments/assets/2ecfe150-e61b-4816-9c81-4ccdc8804190" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT


<img width="882" height="575" alt="image" src="https://github.com/user-attachments/assets/00e78a10-0fb2-4236-8b1b-8abcc3e09157" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="860" height="306" alt="image" src="https://github.com/user-attachments/assets/bb093702-d2ab-443a-bb0a-035ff6f0fb59" />




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="832" height="347" alt="image" src="https://github.com/user-attachments/assets/077790b3-42d8-4ada-8099-0dfaf8e3ed16" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="846" height="386" alt="image" src="https://github.com/user-attachments/assets/4b6ef12c-5f36-4bd1-b592-8800911759d5" />




It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1920" height="1200" alt="Screenshot 2026-08-25 141913" src="https://github.com/user-attachments/assets/34b755bd-6148-478e-8510-2c8da970d7c0" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2026-08-25 142039" src="https://github.com/user-attachments/assets/85014042-8cd4-49e9-ab28-1493dfca0890" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1013" height="1138" alt="Screenshot 2026-08-25 142224" src="https://github.com/user-attachments/assets/ec120c6e-8a31-4b7d-8aa2-906189e2ff4a" />




SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2026-08-25 142352" src="https://github.com/user-attachments/assets/776771e8-f0e3-424d-9405-39f68623fb1c" />




SET logs the information in the xml file under /root/.set directory:
## OUTPUT


<img width="883" height="470" alt="image" src="https://github.com/user-attachments/assets/1c6534ec-ebd2-48d8-92b2-be57ea4625ae" />










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
