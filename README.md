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

<img width="947" height="955" alt="image" src="https://github.com/user-attachments/assets/cccf3017-e86a-47ee-b396-553b2392a8ba" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="742" height="302" alt="image" src="https://github.com/user-attachments/assets/99f7abbd-c3bc-4730-9ea4-7acf13cdb1ca" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="951" height="587" alt="image" src="https://github.com/user-attachments/assets/0a16ee28-871b-4e68-af47-942e912c562d" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="877" height="368" alt="image" src="https://github.com/user-attachments/assets/168a4dc5-b1ba-4639-849b-2534d8f3a505" />


It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="875" height="388" alt="image" src="https://github.com/user-attachments/assets/448530b0-c553-4773-8363-2b5650d93256" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="947" height="1112" alt="image" src="https://github.com/user-attachments/assets/97f27ba5-a4ae-494e-b30b-df97ac38ae8f" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="952" height="1102" alt="image" src="https://github.com/user-attachments/assets/454dfdc5-fb03-4c29-9dae-ed6333b40f4f" />



SET logs the information regarding the Google credentials:
## OUTPUT

<img width="955" height="498" alt="image" src="https://github.com/user-attachments/assets/f373f476-9190-4642-a591-27f45fa39f24" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
