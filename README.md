# Running a Coda Testnet Node on a budget
---
### _Long-term solution to staking Coda and snarking for participation in the Genesis Program_

Coda has given us an incentive to stake Coda on their testnet ahead of their upcoming mainnet release. In the terms of the Genesis Program, participants are required to stake their Coda for an entire year by keeping a node connected to the network. For most participants, dedicated hardware will be used but this can tie up resources for those on a budget. Others will go the virtual private server (VPS) route but this can prove to be even costlier than purchasing dedicated hardware. 

As an example on Google Cloud Platform (GCP), a VPS with 4 virtual CPU cores and 8 GB of RAM can cost nearly $100 per month. GCP will give new users $300 in free credits to try the service, but if the intention is to run for a year, this will equate to a $900 investment! These costs severely limit the ability of many potential participants.

If someone wanted to build a dedicated computer configured for the Coda Testnet, costs could be anywhere from $300 and up. Plus you would want to have an excellent internet connection and some amount of fault tolerance for potential power outages.

I want to participate in Coda's Genesis Program, but cannot justify the costs to run on GCP. I would run Coda on my home computer, but, like many folks I only have one good machine capable of meeting the hardware requirements, and I use it for a lot of other things so can't really justify tying it up just for this. I have other older computers, but for me it doesn't make sense to use them for this, and at the moment I don't have the budget to build a new computer.

**My Solution?**
---
Enter the [**Contabo VPS M SSD**](https://www.anrdoezrs.net/click-9247314-13796470?sid=GitHub). For 8.99 Euros per month, you get six cores of an Intel Xeon processor (either E5-2620v3, E5-2630v4, or 4114 processor) with 16 GB of RAM, 400 GB of SSD disk space, and unlimited traffic on a 400 Mbit/second internet connection with DDoS protection.
<br>
For the pricing, you can select to be charged monthly, or every 3, 6, or 12 months. There is a one-time setup fee of €4.99, but the longer commitments lower the setup fee as follows:
<br>

### Setup Fee
The cost of the one-time setup fee is determined by the billing frequency selected at the time of setup:
- Billed every month: Setup fee is 4.99€
- Billed every 3 months: Setup fee is 3.99€
- Billed every 6 months: Setup fee is 2.99€
- Billed every 12 months: Setup fee is waived

### Total Cost to run for 1 year
Setup fee + server costs
- Billed every month: 112.87€
- Billed every 3 months: 111.87€
- Billed every 6 months: 110.87€
- Billed every 12 months: 107.87€

**Payments**
---
PayPal, Skrill, and Bank Wire Transfers are all accepted, but PayPal is the preferred method of payment. Once you have selected your desired options and make the payment, they will begin provisioning your server. Though this isn't an instant process (and the site says it could take up to 24 hours), my server was ready in under an hour and my login details were emailed to me. The email will include your server's IP address and password which you use to connect to over SSH. You can also use VNC to connect to your server. If you have read this far you _probably_ know how to do this, but I'll try to do a tutorial in the future that details it.
<br>

**Server Review**
---
I originally set my Coda node up on a GCP instance, but soon stopped it once I saw how fast the free credits were going. I then setup a VPS on [**Contabo**](https://www.anrdoezrs.net/click-9247314-13796470?sid=GitHub)  and imported my keys (tutorial in the works) and was able to get back on the testnet just fine. Shortly after, there was a bug on the testnet preventing nodes from joining the main chain, so I shut this VPS down and started to CPU mine the Safex fork of RandomX. With this, I am getting nearly 1 kH/s using four of the six cores available to me, and it has been very stable. Once the new Coda Testnet code is released on 14 Feb 2020 I will reinstall the operating system (from the [**Contabo**](https://www.anrdoezrs.net/click-9247314-13796470?sid=GitHub)  control panel) and get my Coda node back up and running. The service has been great and I haven't experienced any outages or downtime, even running at 100%. Coda staking requires little resources, but snarking work will use 100% CPU for the 5 minutes or so every several hours, so once I switch back to Coda I expect no issues with my VPS staying connected to the network.

I'm very happy with my switch to [**Contabo**](https://www.anrdoezrs.net/click-9247314-13796470?sid=GitHub)  and am happy that I have paid for a year up front! I hope this review has helped, and hope it opens up an option for more people to participate in the Coda Genesis Program!
