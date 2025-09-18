# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="911" height="738" alt="479586245-5738181c-dce0-458c-8b42-afe9500d3663" src="https://github.com/user-attachments/assets/ece0be13-fcbb-4a9c-898e-a73a596893fe" />

### Finding Hosting Company :
<img width="1617" height="847" alt="479586075-785c5332-534a-4754-85d0-645e2ecb075e" src="https://github.com/user-attachments/assets/3419c66f-6e12-4fe7-9677-e5636dd9520c" />

### History of the website :
<img width="1919" height="922" alt="479588035-3fd65f7b-6a24-41dc-b8b5-f1aee477132a" src="https://github.com/user-attachments/assets/87be68bf-ab41-4d29-8661-c529d7ec62ef" />

### ping command :
<img width="1352" height="672" alt="Screenshot 2025-09-18 084850" src="https://github.com/user-attachments/assets/a2744b0b-93a5-4443-8c7b-f78aa0aa4868" />


### whois :
<img width="1328" height="694" alt="image" src="https://github.com/user-attachments/assets/486ce28a-9018-41db-aef1-f5269fd44e94" />


### netcat :
<img width="750" height="128" alt="image" src="https://github.com/user-attachments/assets/c1ece27b-e23c-4d30-bd9e-02d0f6386012" />


### nmap :
<img width="1007" height="406" alt="image" src="https://github.com/user-attachments/assets/776e3f9f-22c5-4f68-9da1-2f39d23bb0f8" />


### whatweb :
<img width="1145" height="642" alt="image" src="https://github.com/user-attachments/assets/e80e34df-02e0-4492-baac-c93ce9e1a73d" />


### httprint :
<img width="630" height="208" alt="479598583-25d1d98e-6ccd-4459-957f-c91ac4edd97e" src="https://github.com/user-attachments/assets/b671f174-01c3-4154-8801-e1b7f21dae74" />

### TCP traceroute :
<img width="747" height="394" alt="479599153-c957bd67-1b5e-42ba-baee-1fa5332cbb47" src="https://github.com/user-attachments/assets/d80ebeae-a9d1-45b2-b3ec-e2241150a1a2" />

### UDP traceroute :
<img width="731" height="527" alt="479599727-7478e1f6-9ed0-4a13-8629-fed1faa85635" src="https://github.com/user-attachments/assets/2780d89c-2653-4b30-b5e9-ff99b4aeb0ee" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
