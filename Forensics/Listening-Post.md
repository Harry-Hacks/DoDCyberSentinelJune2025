# Listening Post
**Category: Forensics**


**Value: 150**

**_Decription:_**
We've intercepted a radio broadcast being bounced off a satellite likely intended for the North Torbian cells located around the world. Do you think you can unravel what they are transmitting?

# Steps
1. First, I downloaded the audio file, then listened to it

2. It contained a series of beeps that sounded sort of like someone putting in a phone number so I thought of using a DTMF decoder

3. I had to install the decoder on my laptop\
`sudo apt install sox multimon-ng`
  
4. Then adjust the audio file to 8000 Hz (I learned this was the standard for DTMF decoders)\
`sox radio.wav -r 8000 -c 1 radio_dtmf.wav`

5. After running this, I got an output with many lines of 0's and 1's\
ex:
`DTMF: 0
DTMF: 1
DTMF: 1
DTMF: 1
DTMF: 1
DTMF: 1
DTMF: 0
DTMF: 1`

6. Then I used ChatGPT to take out the `DTMF:` part and align the numbers to ascii format, then I inputed those into an ascii decoder and got the flag

C1{r4d1o_k1ll3d_th3_t0rb1a_st4r}
