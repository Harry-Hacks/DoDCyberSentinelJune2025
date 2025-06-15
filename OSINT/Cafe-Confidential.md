# Cafe Confidential
**Category: OSINT**


**Value: 75**

**_Decription:_**
Two photos were posted minutes apart by someone of interest. One shows them enjoying a slice of cake in a boutique café; the other captures a well-known landmark in the background. We believe both photos were taken on the same outing. Can you determine exactly which café they visited, and where is it?

Flag format is: C1{Cafe Name_Street Name}

For example, Tom's Cafe located at 31 Mitchell Rd, Boston, MA would be C1{Tom's_Mitchell}.

# Steps
1. First thing I did was download the two images attached, 

<img width="749" alt="Screenshot 2025-06-15 at 11 35 39 AM" src="https://github.com/user-attachments/assets/13ff7aa2-ac14-40e8-b5dd-5cacd82f46f2" />

<img width="993" alt="Screenshot 2025-06-15 at 11 36 00 AM" src="https://github.com/user-attachments/assets/dbfbe7aa-c22e-49ed-8c1a-fb18cf467cd2" />

2. Then I looked at the images, the first is a picture of a cake and I noted the paper the cake was on had a logo of a "P", so I was thinking the Café probably started with the letter P
   
3. The second image was one I was familiar with, it is showing Harrods, a very famous department store in London.
5. I used google maps to find Harrods, saw that it was located on Brompton Rd., and looked at the Café's surrounding the store. Some stood out, there is a 'Prada Caffè' and 'PAUL' both with addresses on Brompton
6. I tried to reverse image search the "P" logo I saw on the paper under the cake. Unfortunately, that did not turn up any leads
<img width="672" alt="Logo search" src="https://github.com/user-attachments/assets/db2a88bf-de33-4287-8ec5-8d470ee266ff" />

7. I then just reverse image searched the entire image of the cake and that yielded better results, with articles popping up about Parker's 
<img width="695" alt="Screenshot 2025-06-15 at 11 54 55 AM" src="https://github.com/user-attachments/assets/ff5fe1e6-a6ae-4bf3-af3c-7234409610f3" />

8. After that I was able to find Parker's and its address 21 Lowndes St

9. Last step was to input the flag, C1{Parkers_Lowndes}

# Takeaways
Looking back, I should have just reverse image searched the whole cake image to begin with, I focused too much on small details (logo) thinking that would break it open instead of just trying something that, to me, seemed too "obvious"

