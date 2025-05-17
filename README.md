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

![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/5795924a-394b-4f4c-8619-2d78fbec34cb)
It displays the following menu and select 2 for Website Attack Vectors:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/86f15a66-74bd-4972-8f90-fe350c8e8fc9)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/db087060-9101-491b-9990-7f639bc729db)
The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/fc80596a-4045-406f-a46d-059ab17fa5a7)
It shows the following screen in which the ip address of the attacker need to be given which is the default value:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/ba6f0a87-ef5d-4b38-95df-15eb99e2a11e)
It shows the following screen in which the option Google can be selected:

![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/22c56f45-f3cf-4d39-8851-553c72d18fd4)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/be737b19-0f40-4078-92a3-92208840632c)
In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/1ac5ac15-a048-466e-a9c8-cb462733b4ed)
SET logs the information regarding the Google credentials:
![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/17bf0508-02be-430b-abb4-b43a842bd9cb)


SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/LOKESHKUMARPANCHATCHARAM/creating-a-backdoor-with-SET/assets/119644432/44445c6a-0254-45ea-a929-9399678dcc42)






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
