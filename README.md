# NAME: SOMESHWAR S
# REGISTER NO: 212224040322
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

![whois](https://github.com/user-attachments/assets/43b3a343-17cf-44fd-97aa-3d74091ec42f)



### Finding Hosting Company :
<img width="778" height="712" alt="image" src="https://github.com/user-attachments/assets/f79765fb-a486-4a36-a14b-f0272bec7043" />


### ping command :
<img width="658" height="481" alt="ping" src="https://github.com/user-attachments/assets/ed28201d-7de5-4bcc-bafb-25472ec5c3b7" />


### Kali Linux:
<img width="777" height="490" alt="nmap1" src="https://github.com/user-attachments/assets/97c6e482-8c84-41f6-a0a4-3dd51acaad00" />


### whois :
<img width="817" height="490" alt="whois" src="https://github.com/user-attachments/assets/8e193814-88c4-4cc3-a2e2-f6874aba62b4" />


### netcat :
<img width="798" height="75" alt="nc" src="https://github.com/user-attachments/assets/5683980b-2e2a-4792-a019-e253becff457" />


### nmap :
<img width="760" height="403" alt="nmap" src="https://github.com/user-attachments/assets/80ca8558-fccf-49e4-936e-9ea4d2e35d80" />

### whatweb :
<img width="780" height="318" alt="whatweb'" src="https://github.com/user-attachments/assets/8c65b3be-a599-4405-a617-aaec91615cde" />

### httprint :
<img width="760" height="65" alt="https" src="https://github.com/user-attachments/assets/5036f636-f4a8-495c-9b6e-c4c013789d1c" />


### TCP traceroute :
<img width="764" height="93" alt="traceroute" src="https://github.com/user-attachments/assets/e84e685f-bb7b-482c-99c2-2a6dd018f71f" />


### UDP traceroute :
<img width="742" height="533" alt="udp" src="https://github.com/user-attachments/assets/bbda408a-8d85-40e5-9ad5-265ddf5b83a7" />



## RESULT:
The information gathering techniques tools/procedure were  identified successfully
