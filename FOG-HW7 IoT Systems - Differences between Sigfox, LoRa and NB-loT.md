---
title: FOG-HW7 IoT Systems - Differences between Sigfox, LoRa and NB-loT
tags: Summary
description: 20201202
---

# WEBINAR Differences between Sigfox, LoRa and NB-loT

URL: https://www.youtube.com/watch?v=vqHOyQK6jJ8

---

The following are some notes from video

---

## What is LPWA(Low Power Wide Area)?

- A new type of network which can connect massive devices, cover wide area and transmit data in long distance with low power consumption. 
    - High density of object
    - Reduce hardware and connectivity cost
    - low data rates
    - Constrained latency

---

## Sigfox, LoRa and NB-IoT
<img src="https://i.imgur.com/RX1fHVr.png" width=600 height=350 />

### sigfox
- Unlicensed Band with Narrow Band
- Limited transmission capacity
- Own sigfox base station 
- Benefits:
    - Higher capacity of objects
    - Higher resistance to noise
- Suitable to transmit data between diffenent countries which have Sigfox basestation 
### LoRa 
- Unlicensed Band with Spread spectrum
- Easily build base station 
- Benefits:
    - Lower susceptibility
- Good for private network but easily have collision and faild transmission in pubilc network 
### NB-IoT
- Licensed Band
- No data limitation
- Mobility

---

## The comparison between Sigfox and LoRa
<img src="https://i.imgur.com/QXrU8ZN.png" width=600 height=350 />


---

## The comparson between Sigfox and NB-IOT
<img src="https://i.imgur.com/2aDJoag.png" width=600 height=350 />

- sigfix is lower cost and power than NB-IoT


<img src="https://i.imgur.com/4qz79T9.png" width=600 height=350 />

- sigfox has it's own way to communicate with base station


---
## Summary
- For common application, I will choose LoRa communication protocl in LAN and unify all information in one node then use NB-IoT to transmit the data
    - LoRa is suitable in private network
    - NB-Iot has mobility


### Thank you! :tiger: 

