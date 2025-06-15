# Packet Whisperer
**Category: Networking**


**Value: 75**

**_Decription:_**
Our blue team intercepted a network capture file. It contains unencrypted HTTP traffic. While skimming through it, analysts believe someone accidentally exposed their login credentials in plain text. Review the PCAP to find the password that the user logged in with.

# Steps
1. Download the attached pcap file, for this I used tshark to filter the file for POST requests, that revealed the password in plain text

![Flag](https://github.com/user-attachments/assets/b0d31fbc-b7b2-42b9-a4bc-38fbada24615)

C1{maybe_TLS_would_be_nice}
