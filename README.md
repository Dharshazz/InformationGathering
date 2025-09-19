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
<img width="734" height="270" alt="image" src="https://github.com/user-attachments/assets/0cbffa40-8f05-4203-b2e4-0cee605ebaa6" />


### TCP traceroute :
<img width="756" height="350" alt="image" src="https://github.com/user-attachments/assets/b5e3d730-6063-4e1e-b246-1ef486353d4f" />


### UDP traceroute :
<img width="1148" height="663" alt="image" src="https://github.com/user-attachments/assets/7a726f73-1223-404a-838f-f7f589a67568" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
