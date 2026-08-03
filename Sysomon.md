# Download Sysmon to Windows VM

### Download Sysmon
The latest version of Sysmon can be downloaded <a href="https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon">here at this link</a>.

<a href="https://learn.microsoft.com/en-us/sysinternals/downloads/sysmon"><img src="https://img.shields.io/badge/-Sysmon_Download_Link-0072b1?&style=for-the-badge&logo=NONE&logoColor=white" /></a>

<img width="2478" height="1478" alt="Screenshot 2026-08-03 111442" src="https://github.com/user-attachments/assets/509eb4a1-42e9-43f6-82fa-69fa51a476db" />

Click on "Download Sysmon"

<img width="798" height="142" alt="Screenshot 2026-08-03 111305" src="https://github.com/user-attachments/assets/f6a2585d-178b-4be8-bf5b-acf5983871f5" />

Go to downloads and open the folder.

<img width="2486" height="1482" alt="Screenshot 2026-08-03 111718" src="https://github.com/user-attachments/assets/04465a38-0a08-49e9-9435-69000853ba8a" />

<img width="1094" height="258" alt="image" src="https://github.com/user-attachments/assets/9bc68e52-7d06-47ab-8da1-5956349b54e1" />

Right click on the folder and choose "Extract All...".

<img width="1900" height="1136" alt="image" src="https://github.com/user-attachments/assets/8057cfbe-ddc9-49df-8cfa-2b5f720ac5a4" />

click "Extract again.

<img width="1490" height="878" alt="image" src="https://github.com/user-attachments/assets/806d3b6f-201d-45db-bf19-b238a1cd4fcc" />

### Download Sysmon Configuration

Go to Olaf's Github <a href="https://github.com/olafhartong/sysmon-modular">here at this link</a>.

<a href="https://github.com/olafhartong/sysmon-modular"><img src="https://img.shields.io/badge/-Sysmon_Configuration_Download_Link-0072b1?&style=for-the-badge&logo=NONE&logoColor=white" /></a>

<img width="2480" height="1482" alt="image" src="https://github.com/user-attachments/assets/adb9bde8-b205-4ff1-8ecd-9d3d24069f5e" />

Scroll all the way down until you see "sysmonconfig.xml".

<img width="1514" height="80" alt="image" src="https://github.com/user-attachments/assets/821b6cb4-3c02-4b7f-b090-a12d9dea746d" />

click on it.

<img width="2480" height="1472" alt="image" src="https://github.com/user-attachments/assets/60a1513c-5462-43b3-b798-b1e903707add" />

Click on "RAW" in the upper right hand corner.

<img width="540" height="116" alt="image" src="https://github.com/user-attachments/assets/29aab554-2710-482d-a679-efa4356a57b4" />


Right click anywhere in the window and choose save as.

<img width="2482" height="1482" alt="image" src="https://github.com/user-attachments/assets/f6b1e7f2-c3b1-4c5a-ae1e-e8ccd087df4f" />

Save it inside the Sysmon directory.

<img width="1480" height="914" alt="image" src="https://github.com/user-attachments/assets/754e426d-be3e-4569-8bf9-1fa94223ac03" />

Open the start menue then type in "Powershell". Right click on Powershell and open it as an administrator.

<img width="2482" height="1480" alt="image" src="https://github.com/user-attachments/assets/b214de62-23c5-4e1f-9581-5cdf2664c19e" />


Click "Yes" when prompted by UAC.

<img width="1112" height="724" alt="image" src="https://github.com/user-attachments/assets/879b271c-b5f2-4d55-9978-f583b2acd8b3" />

Go back to the windows file explorer and click on the search bar. Copy the path. 

<img width="1896" height="1136" alt="Screenshot 2026-08-03 131446" src="https://github.com/user-attachments/assets/795e61ac-edaf-4a11-ab9b-b49eb5db38c8" />

Return to Powershell type:
```
cd
```
which is short for "change directory". Then paste in the path to our Sysmon folder.

I also typed `ls`, is an alias for Powershell's native command `GetChiledItem` to reveal the contents of the folder and confirm I'm in the right place.

<img width="2366" height="986" alt="Screenshot 2026-08-03 132346" src="https://github.com/user-attachments/assets/496a9ef0-39e3-49d7-a837-3fe4d0ebd3b7" />












