---
title: FOG-HW5 5G Network Deployment
tags: Summary
description: 2020/11/19
---

# 5G Network Deployment 

[TOC]

<!-- Put the link to this slide here so people can follow -->
URL: https://www.youtube.com/watch?v=z49JGni3hbw

---

there are some notes from the video

---
Nowadays, 5G mobile communication network is coming into our life. 
In 2019~2020, each telecom operator spend lots of money bidding for 5G spectrum in order to have sufficient spectrum to service lots of customers.
However, deploying 5G infrastructures also costs lots of money and time.  
From 3GPP standards, they provide non-standalone(NSA) and standalone(SA) for 5G network.
- 5G system architecture is made of the 5G-UE, 5G-RAN and the 5G Core Network.
- NSA: the radio part is 5G New Radio (NR) and the core part is 4G Evolved Packet Core (EPC); it is called Non-Stand Alone (5G Radio + 4G Core = NSA).
- SA: the radio part is 5G NR and the core part is 5G core; then it is called Stand Alone (5G Radio + 5G Core = SA).

![](https://i.imgur.com/CRXJ1Hw.png)

## Key Concepts
we have some options for 5G deployment, before we talk more details about deploying options, there are some key concepts we need to understand

![](https://i.imgur.com/p6kBByT.png)
- Master Node（MN）: The main base staion for whole network architecture
    - Provide radio resources toward the user
- Secondary Node(SN): The assistant base staion for whole network architecture
    - Provide radio resources toward the user
- Master Cell Group Bearer(MCG): It's an over the air user-plane bearer which is associated with an MN
- Secondaty Cell Group Bearer(SCG): It's an over the air user-plane bearer which is associated with an SN
- Split Bearer: A bearer for which traffic is routed via LTE and/or NR bearer
- Master Split Bearer: Traffic is splitted at MN node
    - It can assist SN node to transmit the data to UE   
- Secondary Split Bearer: Traffic is splitted at SN node 
    - It can assist MN node to transmit the data to UE 


## Deplyment Options
![](https://i.imgur.com/uu54pS6.png)
 
### Advantages/Disadvantages comparison for each option
![](https://i.imgur.com/XCTF7gM.png)

## Main concern form the video

- Among all deployment options, what are common parts and differences
    - SA: 1,2,5
    - NSA: 3,4,7
    - 5G Core: 2,4,5,7
    - LTE EPC: 1,3 
    
- Why the differences are needed 
    - Catering to different rigions which have different infrastructures and technologies

## Summary
- Different regions for 5G deployment will use the option which is suitable for their situation now.
- Spectrum, regulation, UE Availability, NR Coverage,Capacity, Services Offered and Interworking are also should be consider.
- Strategic migration will be Option1 -> NSA Option 3x -> SA Option 2 
## Reference :cat:

https://www.mediatek.com/blog/5g-what-is-standalone-sa-vs-non-standalone-nsa
https://medium.com/@5gnr/5g-nr-en-dc-bearer-concept-291e21b79b38