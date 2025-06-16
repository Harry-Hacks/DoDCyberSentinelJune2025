# Field Report Mayhem
**Category: Web Security**


**Value: 150**

**_Decription:_**
We've gained access to the Juche Jaguar’s Field Reports archive through an operative's use of weak credentials. Upon logging in, the operative sees their previous field reports and can file new ones. Somewhere in here, I am sure some 'leet' agent stashed the Supreme Leader's secret pizza discount code!
Log in to the portal at: http://35.245.106.190/login.html

Use the credentials: `1234:spudpotato`
# Steps
1. First step was to log into the website with the credentials provided, that brought up a page of Agent 1234
<img width="310" alt="Screenshot 2025-06-16 at 9 40 03 PM" src="https://github.com/user-attachments/assets/6780f88f-4db9-491d-b22c-2a51fb9a6547" />

2. I clicked on each of the 'Available Reports' to see if there was any hints inside of those descriptions

3. I then re-read the description of the and noticed the sentence about 'leet' agent, knowing that this is associated to the number 1337, I changed the id in the browser to 1337

4. http://35.245.106.190//dashboard.php?id=1337&code=IJ56KL

5. This brought up a different dashboard with more reports, one of them contained the flag in the description

6. Debrief: I extracted the Supreme Leader's secret pizza-order
7. discount code: CH1{ID0R_F13LD_R3P0RT}. The pizza delivery arrived
