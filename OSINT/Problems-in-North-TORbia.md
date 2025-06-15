# Problems in North TORbia
**Category: OSINT**


**Value: 150**

**_Decription:_**
We were given a ransom note but none of our files were encrypted. Regardless, could you run it back and see what information could be gleaned from it?

<img width="549" alt="Screenshot 2025-06-15 at 12 22 52 PM" src="https://github.com/user-attachments/assets/bbe5717a-7e76-4a18-9b19-6025217489c1" />

# Steps
1. First I opened the attached note.txt file, and read through

2. I saw that there was a .onion url that they were requesting payment to be sent to
    SEND PAYMENT TO:
    http://jjpwn5u6ozdmxjurfitt42hns3qovikeyhocx5b2byoxgupnuzd2vkid.onion/
   
3. I opened TOR and went to that address and saw this webpage
<img width="1133" alt="Screenshot 2025-06-15 at 12 25 54 PM" src="https://github.com/user-attachments/assets/25345633-321d-44b6-afe6-2e7f097c79c9" />

4. After being on the webpage I viewed page source and saw the flag embedded.
![Flag](https://github.com/user-attachments/assets/32e082f9-c985-4618-9737-1846c4046bd8)

C1{h1dd3n_f13lds_0f_0ni0ns}

# Takeaways
Overall, this was a pretty straightforward it was a good excersise into embedded or hidden fields in html

