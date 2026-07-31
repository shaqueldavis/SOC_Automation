### Download Windows ISO

Go to Microsoft's website via the link below, scroll down, and click download now under "create Windows 11 installation media".
  
<a href="https://www.microsoft.com/en-ca/software-download/windows11"><img src="https://img.shields.io/badge/-Download_Link-007ACC?&style=for-the-badge&logo=microsoft&logoColor=white" /></a>

<br>

<img width="2880" height="1620" alt="image" src="https://github.com/user-attachments/assets/024f3522-e135-4425-b6cd-94b9b6d0527d" />


<br>
<br>
<br>
<br>

Download the file to a dedicated folder. I personally like to download it to a folder on my desktop to make it easy to track and locate.

<br>

after the file has downloaded, double click on the .exe file and click Yes at the UAC pop up window. 

<br>

<img width="1754" height="476" alt="image" src="https://github.com/user-attachments/assets/9b771a31-a9bc-4d26-a08c-b00e6faa2eca" />


<br>
<br>
<br>
<br>

Except the license terms.

<br>

<img width="1300" height="1142" alt="image" src="https://github.com/user-attachments/assets/a9faee0d-5a32-4da1-9f3b-0a0ca1688d72" />

<br>
<br>
<br>
<br>

Keep "use the recommended settings for this PC" checked and hit next.

<br>

<img width="1292" height="1138" alt="image" src="https://github.com/user-attachments/assets/f990a1e2-0ef5-4de2-95a9-25fcc3fdf909" />


<br>
<br>
<br>
<br>

Choose "ISO file" and hit next

<br>

<img width="1298" height="1140" alt="image" src="https://github.com/user-attachments/assets/7f99415c-c05a-487f-9e0f-08a3edfda5ce" />


<br>
<br>
<br>
<br>

Save the ISO file to the same folder where you downloaded the original exe file. <br>
A download window will pop up, and you will see the status of the progression. This will take a little while.

<br>

<img width="1294" height="1136" alt="image" src="https://github.com/user-attachments/assets/82efbe56-69f2-415d-871a-2b1dfbb7a315" />


<br>
<br>
<br>
<br>

Hit finish once it is completed and you will see the ISO file in your folder.

<br>

<img width="1286" height="1134" alt="image" src="https://github.com/user-attachments/assets/6afdfab2-7419-4697-bb7b-6f29bd152ab1" />

<br>
<br>
<br>
<br>

#

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



#
#
#
#
#
#
#
#
#

Name your virtual machine. I chose to name mine “Windows 11 SOC lab” because I will likely only use it for the purpose of this Lab. <br>
Also click browse and choose the location where you want your VM to be stored. Then hit Next


<img width="854" height="830" alt="image" src="https://github.com/user-attachments/assets/f8f22b32-06c8-463f-b0e6-d76912948cc3" />

Keep the default of “only files needed to support a TPM are encrypted…”. Encrytpting all files could make moving, recovering, or troubleshooting the VM less convenient. <br>
**Choose a password that you will remember.** write it down if you need to.


<img width="846" height="832" alt="image" src="https://github.com/user-attachments/assets/6d50cb39-c96d-4fae-aa16-aa8f780fd834" />

Go ahead with the recommended 64 GB setting along with “split virtual disk…”. The split virtual disk setting will make the VM easier to move. <br>
Click next.


<img width="852" height="832" alt="image" src="https://github.com/user-attachments/assets/1023673e-523e-4b9e-a6ae-ee9e9f6ddaac" />

Click customize hardware and bump the memory up to 6 GB.

<img width="854" height="826" alt="image" src="https://github.com/user-attachments/assets/e8656ea0-2bd5-490e-9040-149949596791" />

<img width="1494" height="1396" alt="image" src="https://github.com/user-attachments/assets/e595224a-80c6-46a2-b895-2b32b9e1e079" />

<img width="850" height="832" alt="image" src="https://github.com/user-attachments/assets/b1baa4cf-58ff-4438-b50b-e36ac1f5801e" />

<img width="674" height="458" alt="image" src="https://github.com/user-attachments/assets/ebd3a2b6-ed2d-4e79-affd-27c3c7a032c5" />

<img width="2480" height="1440" alt="image" src="https://github.com/user-attachments/assets/e353c6a0-fd09-4f3c-99bc-68b93f1d7f13" />

<img width="2444" height="1324" alt="Screenshot 2026-07-30 154129" src="https://github.com/user-attachments/assets/75942256-6dce-497c-a161-b3364daf0413" />

<img width="1084" height="68" alt="image" src="https://github.com/user-attachments/assets/5f810368-5881-44be-bc71-8b943961579b" />

<img width="52" height="58" alt="Screenshot 2026-07-30 154150" src="https://github.com/user-attachments/assets/20903b1c-1d31-4f4c-925e-77ff50c9ffcf" />

<img width="1666" height="900" alt="Screenshot 2026-07-30 154222" src="https://github.com/user-attachments/assets/8924299a-65fd-4d54-aa00-3d3ba6a8dee8" />

When the words _________________ appear at the top of the screen hit `enter`. if you wait too long the words ____________ will appear underneath and it will pause for a moment before taking you back to the previous screen.

<img width="2480" height="1346" alt="Screenshot 2026-07-30 154733" src="https://github.com/user-attachments/assets/d75f15b9-c330-4507-a351-194542c5d946" />

<img width="2466" height="1364" alt="Screenshot 2026-07-30 155004" src="https://github.com/user-attachments/assets/a9851c03-d5f9-4d52-9f70-62c2e87d28a9" />

<img width="2478" height="1366" alt="image" src="https://github.com/user-attachments/assets/0b0e1e69-e694-4b6d-aed4-85e95e139fe7" />

<img width="2472" height="1356" alt="image" src="https://github.com/user-attachments/assets/dc308d1b-ec7a-410c-9d83-ae38ce1ee866" />

<img width="2472" height="1336" alt="image" src="https://github.com/user-attachments/assets/c370e005-5bca-43b5-a1b1-fce47bb37e1d" />

<img width="2476" height="1362" alt="image" src="https://github.com/user-attachments/assets/ec70ba4c-5274-4791-8449-e9515d581dd4" />

<img width="2468" height="1348" alt="image" src="https://github.com/user-attachments/assets/70a83a09-c8d4-42aa-9f5f-45a3781dee55" />

<img width="2470" height="1330" alt="image" src="https://github.com/user-attachments/assets/ab98f3ad-c317-4e16-be0b-b999cedb9591" />

<img width="2468" height="1344" alt="image" src="https://github.com/user-attachments/assets/fa75627b-b1a8-43c6-913c-06ee8763e7de" />

<img width="2464" height="1336" alt="image" src="https://github.com/user-attachments/assets/ebf0e957-6023-40b6-b307-7a081967bc63" />

<img width="2470" height="1338" alt="image" src="https://github.com/user-attachments/assets/33370ea3-8a72-4c7b-88a2-f8b6406d2341" />

<img width="2472" height="1346" alt="image" src="https://github.com/user-attachments/assets/0a54f18d-e71a-4da8-b673-9679c8108490" />

<img width="2468" height="1318" alt="image" src="https://github.com/user-attachments/assets/85551f45-12f3-4d71-b63d-9e34a0809e53" />

<img width="2486" height="1340" alt="image" src="https://github.com/user-attachments/assets/6e0ce712-dcf7-4c11-bcc4-1d2745e5c1a2" />

<img width="2474" height="1346" alt="image" src="https://github.com/user-attachments/assets/a1e91516-5665-452f-b983-c62bcc059595" />

<img width="2472" height="1368" alt="image" src="https://github.com/user-attachments/assets/2b4c9b89-ad49-48d4-92c8-cdcce04d0ecc" />

<img width="2474" height="1368" alt="Screenshot 2026-07-30 161856" src="https://github.com/user-attachments/assets/c328249c-7232-4795-a60d-4e82c45edc5b" />

<img width="2478" height="1372" alt="Screenshot 2026-07-30 161915" src="https://github.com/user-attachments/assets/43702315-2939-4ce7-ba59-9ef0096160ed" />

<img width="2474" height="1362" alt="image" src="https://github.com/user-attachments/assets/f9d6a16a-129c-4f5c-ab43-1a358d6f63d3" />

<img width="2476" height="1370" alt="image" src="https://github.com/user-attachments/assets/efb7984f-3033-4094-8916-ff3ae695ea2d" />

<img width="2470" height="1328" alt="image" src="https://github.com/user-attachments/assets/5acb7308-022c-4ce3-8357-532232f41bf5" />

<img width="2472" height="1362" alt="image" src="https://github.com/user-attachments/assets/c065fccf-bb1a-4005-a492-26d75389b5db" />

<img width="2474" height="1368" alt="image" src="https://github.com/user-attachments/assets/c159ef41-4625-4388-9cfb-7ac548cb1e78" />

<img width="2472" height="1364" alt="image" src="https://github.com/user-attachments/assets/a3dddf9a-1d9c-4c9e-a16a-87fb8b0b110a" />

<img width="2474" height="1366" alt="image" src="https://github.com/user-attachments/assets/0d2f4572-5ecc-4f0d-b43d-b72d6f8e9194" />

<img width="2480" height="1364" alt="image" src="https://github.com/user-attachments/assets/778bfdb4-bc1b-443d-85d3-b4bbbf59552b" />

<img width="2472" height="1366" alt="image" src="https://github.com/user-attachments/assets/5eb29fb5-d7f0-4e7c-b717-6da33c9a749b" />

<img width="2474" height="1366" alt="image" src="https://github.com/user-attachments/assets/fa46c947-8510-4c71-bade-7e621aaa8352" />

<img width="2480" height="1378" alt="image" src="https://github.com/user-attachments/assets/1883cbb7-b7cb-4357-ba8e-21938e352736" />

<img width="2476" height="1364" alt="image" src="https://github.com/user-attachments/assets/95cef6af-a264-412d-bc89-6d7f0b6c7a06" />


#
#
#


<img width="2466" height="1372" alt="image" src="https://github.com/user-attachments/assets/12c6069b-fcde-430a-be19-22d7e1ebf60d" />

<img width="2474" height="1366" alt="image" src="https://github.com/user-attachments/assets/e995b1ee-bf98-4711-aec4-698f5ff1e861" />

<img width="2476" height="1368" alt="image" src="https://github.com/user-attachments/assets/4e71d99f-c2d1-4bc4-ad30-cec8e8f6e57b" />

<img width="2470" height="1360" alt="image" src="https://github.com/user-attachments/assets/ccdbd9bc-4102-4594-bf12-5efb5884a06b" />

<img width="2466" height="1364" alt="image" src="https://github.com/user-attachments/assets/d50a5789-070c-435e-bd79-fae4a29d1742" />

<img width="2474" height="1364" alt="image" src="https://github.com/user-attachments/assets/0b69c3d2-6547-4b2f-96ae-5e1fbbf139d1" />

<img width="2476" height="1366" alt="image" src="https://github.com/user-attachments/assets/d29c3e8d-d5f4-40d5-942c-1a0172ca5fb1" />

<img width="2480" height="1372" alt="image" src="https://github.com/user-attachments/assets/b844ba69-e6ce-484d-aeee-804be99f9200" />




















