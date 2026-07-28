# Draw Diagram with Draw.io

In this phase we will Create a diagram to map out how we want to build our lab logically. This way we understand how data flows and what the components are that make it all work.

### 1. Go to Draw.io and Lay out Components

<a href="https://www.drawio.com/"><img src="https://img.shields.io/badge/-Draw.io-D35400?&style=for-the-badge&logo=draw.io&logoColor=white" /></a>

NOTE: The tool is called Draw.io, but the website is www.Drawio.com

<br>
<br>

Click: `Start Diagraming`

<img width="1310" height="1032" alt="image" src="https://github.com/user-attachments/assets/668668d5-d93e-4080-a889-a298487ef0c0" />

This will take you to the Draw.io diagram app webpage.

<br>
<br>

On the lefthand side you will see a search box.

<img width="508" height="288" alt="image" src="https://github.com/user-attachments/assets/1d64ac1f-05fa-4b52-9d84-fe0b6e37fd3b" />

Type `PC` into the search box and hit enter. Drag and draw the icon of your choice to the canvas. This will serve as your Windows 10 Client Wazuh Agent.

Double click the icon to activate the text feature and begin typing. label the machine: `Windows 10 Client Wazuh Agent`.

Right click the PC and duplicate it. Drag the duplicate over to the right and name it: `SOC Analyst`.

Go to the search box again and look for a `router`.  Drag and draw the icon of your choice to the canvas above the PC. Double click the icon to activate the text feature and name it `router`.

Go to the search box one more time and type `internet`. Drag and draw the icon of your choice to the canvas above the router and name it `Internet`.

Right click the internet icon and duplicate it 3 times. place one to the left of the internet, one above it, and one to the right. <br>
name the one to the left: `Wazuh manager` <br>
the one above: `Shuffle` <br>
the one to the right: `TheHive` <br>

<img width="1222" height="1304" alt="image" src="https://github.com/user-attachments/assets/9b352d7c-fcb2-4f21-a5df-9692e7a875a8" />

<br>
<br>
<br>
<br>

### 2. Map out workflow


Then hover over the icon with your mouse. you will see 4 arrows around it.

Grey link from Windows 10 Client Wazuh Agent to the router represents sending of events over to the Wazuh manager.

https://www.drawio.com/



---------------------------------------------

<img width="760" height="978" alt="SOC automation" src="https://github.com/user-attachments/assets/ba934b8b-54cc-4986-aa93-dbd096482c8e" />




