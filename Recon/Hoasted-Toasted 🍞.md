# Packet Hoasted Toasted 🍞
**Category: Recon**


**Value: 150**

**_Decription:_**
We have discovered what we believe is a North Torbian public website and have suspicions there is a secret internal-only site hidden there as well. Figure out how to connect to the hidden site and find the flag!

The sites is at https://not-torbian.ethtrader-ai.com/

# Steps
1. Opened the website and read the page 
<img width="934" alt="Website" src="https://github.com/user-attachments/assets/8dd7cca5-52b9-4ae4-91ca-b7767461af3c" />

2. I then performed an SSL Certificate inspection since the site mentioned "Please disregard any unusual digital signatures you might encounter. They are certainly not related to any internal governmental systems." This pointed out to me that there also might be a site called internal.not-torbian.ethtrader-ai.com/

3. openssl s_client -connect not-torbian.ethtrader-ai.com:443 -servername internal.not-torbian.ethtrader-ai.com

4. This got a suspicious DNS entry with DNS:definitelynotaflag.north.torbia

5. In the subdomain was the flag

C1{vH0st_S4n_M4g1c_R3ve4l3d}
