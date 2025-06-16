# Hidden in Plain Sight
**Category: Forensics**


**Value: 75**

**_Decription:_**
Analysts recovered a suspicious image from a threat actor’s social media account. At first glance it looks like an innocent selfie - but insiders suggest that a flag might be hiding in the image metadata. Can you extract it?


This was the file included:
<img width="295" alt="Screenshot 2025-06-16 at 10 07 20 PM" src="https://github.com/user-attachments/assets/56c1b91b-ca6b-4f8b-ac3e-e383165a033c" />

# Steps
1. Knowing that this was also a metadata challenge, I used the command `exiftool`
2. This is the result:

`exiftool selfie.png | grep C1`

`Comment : C1{smile_youre_flagged}`
