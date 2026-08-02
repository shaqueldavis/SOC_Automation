# For a separate home-lab VM:

This part of the lab **may not apply to everyone**. It is particularly for anyone who has had a Microsoft account for some time now. 

If this is the case for you, Microsoft is likely set up to sync a lot of your data in ways you may be unaware of. 

For me I only have one windows machine, so I’ve never noticed this prior to creating a virtual machine. That said, I was surprised to open Microsoft Edge in my VM and see that my passwords from various personal accounts were saved within it. I also noticed multiple personal folders from my one drive appearing on my desktop.

Needless to say, I deleted the entire VM and started from scratch. Though this concern doesn’t prevent us from taking the steps needed for the lab, it's a good security practice to keep isolated machines isolated. 

For that reason, I have included these steps to un-sync any personal information you may have connected to your Microsoft account from your Windows VM.

**Note: All of these steps can be skipped if:
- You do not currently have a microsoft edge account.
- You don’t care if you information syncs with your VM
- You want to make make a brand new account solely for this lab

## 1. Turn off Edge synchronization.

Microsoft Edge stores a lot of your browser information such as passwords, and history. You probably don’t want your bank information floating around in your disposable VM so…

Open Microsoft Edge web browser and go to settings

<br>

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/90d65738-5a79-40b7-b9cf-67191e931dd5" />

<br>
<br>
<br>
<br>

Select Sync

<br>

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/c79d1cc4-e142-4a5e-87a0-97cec5137253" />

<br>
<br>
<br>
<br>

Turn off all of the toggles

<br>

<img width="2880" height="1800" alt="image" src="https://github.com/user-attachments/assets/4f37cfb7-561c-4967-8e96-ebf8f71b29a0" />

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





Uninstall or unlink OneDrive.
Turn off Windows Backup under:
