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

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/2d8836aa-245f-4c5c-9819-358ee972b827)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/3ccfce9c-ebe8-459f-94a4-5ab09b96a607)

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/064f9d58-8f57-4ba0-b22e-c114b31a3517)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/47f6a94f-2e84-4efb-b777-0dce441a0ea7)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/4f998fca-369b-4188-bb0f-2a76f183fe72)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/aeb9127c-335c-4689-8e2c-6a755b0f6a37)

It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/3bd2573d-a54e-4a85-86ed-642b30ea6d3e)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/170a9d5b-496f-4eb4-bb61-8d141c88d8d6)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/13c65448-126e-450a-b1b0-5f7df6b1c9a9)

SET logs the information regarding the Google credentials:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/cfbff4b8-d7ff-46d9-a1d2-645cf20080f5)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:
![image](https://github.com/Karthikeyan21001828/creating-a-backdoor-with-SET/assets/93427303/e63b5ccd-6909-403d-ab16-ba99809e8823)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
