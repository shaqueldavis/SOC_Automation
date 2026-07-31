### Set Up Windows ISO on VM

My version of this lab will require you to already have VM Workstation pro downloaded on your computer. My goal is to create another repository in the future that walks through the steps to do so. However, In the meantime check out YouTube University and even ChatGPT for guided info.

<br>

Open up VM Workstation pro and navigate to the “Home” tab at the top left of the window.<br>
Click “create a new virtual machine”.

<br>

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/dbedc5b8-1fbc-4508-868b-908fff619f56" />

<br>
<br>
<br>
<br>

Keep the default selection of “typical (recommended)" for your configuration settings and hit next.

<br>

<img width="852" height="826" alt="Screenshot 2026-07-30 115037" src="https://github.com/user-attachments/assets/5357bdf2-50fe-4e46-b0c4-312cebdd0a27" />

<br>
<br>
<br>
<br>

Click browse next to “Installer disc image file (iso):” and locate the ISO file we downloaded earlier. <br>
Once you have selected your desired file path click next.

<br>

<img width="848" height="826" alt="image" src="https://github.com/user-attachments/assets/52704b3a-fe5b-4224-acd0-9aefc3d5ac6c" />

<br>
<br>
<br>
<br>

Name your virtual machine. I chose to name mine “Windows 11 SOC lab” because I will likely only use it for the purpose of this Lab. <br>
Also click browse and choose the location where you want your VM to be stored. Then hit Next

<br>

<img width="854" height="830" alt="image" src="https://github.com/user-attachments/assets/f8f22b32-06c8-463f-b0e6-d76912948cc3" />

<br>
<br>
<br>
<br>

Keep the default of “only files needed to support a TPM are encrypted…”. Encrytpting all files could make moving, recovering, or troubleshooting the VM less convenient. <br>
**Choose a password that you will remember.** write it down if you need to.

<br>

<img width="846" height="832" alt="image" src="https://github.com/user-attachments/assets/6d50cb39-c96d-4fae-aa16-aa8f780fd834" />

<br>
<br>
<br>
<br>

Go ahead with the recommended 64 GB setting along with “split virtual disk…”. The split virtual disk setting will make the VM easier to move. <br>
Click next.

<br>

<img width="852" height="832" alt="image" src="https://github.com/user-attachments/assets/1023673e-523e-4b9e-a6ae-ee9e9f6ddaac" />

<br>
<br>
<br>
<br>

Click customize hardware and bump the memory up to 6 GB.

<br>

<img width="854" height="826" alt="image" src="https://github.com/user-attachments/assets/e8656ea0-2bd5-490e-9040-149949596791" />

<br>

<img width="1494" height="1396" alt="image" src="https://github.com/user-attachments/assets/e595224a-80c6-46a2-b895-2b32b9e1e079" />

<br>
<br>
<br>
<br>

Click close on the hardware window after changing the memory settings. Then click finish. <br>
You will then see a loading bar.

<br>

<img width="850" height="832" alt="image" src="https://github.com/user-attachments/assets/b1baa4cf-58ff-4438-b50b-e36ac1f5801e" />

<br>
<br>
<br>
<br>

After this the VM will be created and you might get this pop up message about “side channel mitigations enabled”. Just click ok. This setting essentially means that your VM is being restricted from observing certain information that could give it insight to whats happening on your host computer.

<br>

<img width="674" height="458" alt="image" src="https://github.com/user-attachments/assets/ebd3a2b6-ed2d-4e79-affd-27c3c7a032c5" />

<br>
<br>
<br>
<br>

A Black loading screen will pop up for a little while. It should take no more than 5 minutes to progress to the next screen. <br>
You may also notice a yellow bare across the bottom of the screen. Ignore it until you are finished installing everything.

<br>

<img width="2480" height="1440" alt="image" src="https://github.com/user-attachments/assets/e353c6a0-fd09-4f3c-99bc-68b93f1d7f13" />

<br>
<br>
<br>
<br>

Now you will see the “Boot Manager” appear. <br>

<br>

<img width="2444" height="1324" alt="Screenshot 2026-07-30 154129" src="https://github.com/user-attachments/assets/75942256-6dce-497c-a161-b3364daf0413" />

<br>
<br>
<br>
<br>

The window may be very small. At the top of the VM interface in the tool bar, click the “Free stretch” icon to make it larger. 

<br>

<img width="1084" height="68" alt="image" src="https://github.com/user-attachments/assets/5f810368-5881-44be-bc71-8b943961579b" />

<br>

<img width="52" height="58" alt="Screenshot 2026-07-30 154150" src="https://github.com/user-attachments/assets/20903b1c-1d31-4f4c-925e-77ff50c9ffcf" />

<br>
<br>
<br>
<br>

Now hit  enter to “Boot normally”.

<br>

<img width="1666" height="900" alt="Screenshot 2026-07-30 154222" src="https://github.com/user-attachments/assets/8924299a-65fd-4d54-aa00-3d3ba6a8dee8" />

<br>
<br>
<br>
<br>

When the words “Press any key to boot from CD or DVD” appear at the top of the screen hit enter. If you wait too long the words “Unsuccessful…” may appear underneath and it will pause for a moment before taking you back to the previous screen. 

<br>

<img width="2480" height="1346" alt="Screenshot 2026-07-30 154733" src="https://github.com/user-attachments/assets/d75f15b9-c330-4507-a351-194542c5d946" />

<br>
<br>
<br>
<br>

The set up for windows will begin to load

<br>

<img width="2466" height="1364" alt="Screenshot 2026-07-30 155004" src="https://github.com/user-attachments/assets/a9851c03-d5f9-4d52-9f70-62c2e87d28a9" />

<br>
<br>
<br>
<br>

For language I’m going with the default of “English”, then hitting next

<br>

<img width="2478" height="1366" alt="image" src="https://github.com/user-attachments/assets/0b0e1e69-e694-4b6d-aed4-85e95e139fe7" />

<br>
<br>
<br>
<br>

Again I’ll hit next for the default of “US”. That’s where I bees.

<br>

<img width="2472" height="1356" alt="image" src="https://github.com/user-attachments/assets/dc308d1b-ec7a-410c-9d83-ae38ce1ee866" />

<br>
<br>
<br>
<br>

At the “select setup option” choose “Install Windows 11” and check the box next to “I agree everything will be deleted including files, apps, and settings”. In our case this is irrelevant because there is nothing currently on the VM. After that click next.

<br>

<img width="2472" height="1336" alt="image" src="https://github.com/user-attachments/assets/c370e005-5bca-43b5-a1b1-fce47bb37e1d" />

<br>
<br>
<br>
<br>

When prompted to enter a product key click I don’t have a product key at the bottom and then hit next.

<br>

<img width="2476" height="1362" alt="image" src="https://github.com/user-attachments/assets/ec70ba4c-5274-4791-8449-e9515d581dd4" />

<br>
<br>
<br>
<br>

You will see a loading screen for a few minutes. Wait patiently please.

<br>

<img width="2468" height="1348" alt="image" src="https://github.com/user-attachments/assets/70a83a09-c8d4-42aa-9f5f-45a3781dee55" />

<br>
<br>
<br>
<br>

On the next page at “select image” choose “Windows 11 Pro” and hit next.

<br>

<img width="2470" height="1330" alt="image" src="https://github.com/user-attachments/assets/ab98f3ad-c317-4e16-be0b-b999cedb9591" />

<br>
<br>
<br>
<br>

On the next page at “select image” choose “Windows 11 Pro” and hit next.

<br>

<img width="2468" height="1344" alt="image" src="https://github.com/user-attachments/assets/fa75627b-b1a8-43c6-913c-06ee8763e7de" />

<br>
<br>
<br>
<br>

Accept the license agreement. 

<br>

<img width="2464" height="1336" alt="image" src="https://github.com/user-attachments/assets/ebf0e957-6023-40b6-b307-7a081967bc63" />

<br>
<br>
<br>
<br>

Again it will load for a little while.

<br>

<img width="2470" height="1338" alt="image" src="https://github.com/user-attachments/assets/33370ea3-8a72-4c7b-88a2-f8b6406d2341" />

<br>
<br>
<br>
<br>

You will then see theVM disk we created earlier. Select it and hit next.

<br>

<img width="2472" height="1346" alt="image" src="https://github.com/user-attachments/assets/0a54f18d-e71a-4da8-b673-9679c8108490" />

<br>
<br>
<br>
<br>

Now click install.

<br>

<img width="2468" height="1318" alt="image" src="https://github.com/user-attachments/assets/85551f45-12f3-4d71-b63d-9e34a0809e53" />

<br>
<br>
<br>
<br>

This time it will load for quite a while. So feel free to grab a snack or something. 

<img width="2486" height="1340" alt="image" src="https://github.com/user-attachments/assets/6e0ce712-dcf7-4c11-bcc4-1d2745e5c1a2" />

<br>

<img width="2474" height="1346" alt="image" src="https://github.com/user-attachments/assets/a1e91516-5665-452f-b983-c62bcc059595" />

<br>
<br>
<br>
<br>
