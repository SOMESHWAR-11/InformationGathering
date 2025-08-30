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
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/58803e41-5191-4be3-b5f6-314679e06f7b" />
<img width="1918" height="1018" alt="image" src="https://github.com/user-attachments/assets/565e7608-2cab-4d1a-a530-9d5b20da0580" />
<img width="1918" height="1015" alt="image" src="https://github.com/user-attachments/assets/094d949b-8a0f-4eb1-8224-2ffe2216a478" />
<img width="1917" height="1016" alt="image" src="https://github.com/user-attachments/assets/baa798f8-8687-486b-a839-92d0e30cad74" />

### Finding Hosting Company :
<img width="1919" height="972" alt="image" src="https://github.com/user-attachments/assets/d4f87da2-4a71-47f1-8ab5-f3cd795c02f0" />
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/aec6b44d-5411-47d9-8c9a-6ee23a8c7850" />
<img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/f8d5bf8c-d643-48d5-87ed-d933fa54077d" />

### History of the website :
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/21ee599e-e6c5-475a-af25-06ada662ab46" />
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/3c409310-4f45-44c4-a576-46a756f61eb8" />
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/5e6da515-1465-4e25-93b5-e98fb0f553ff" />
<img width="1919" height="1015" alt="image" src="https://github.com/user-attachments/assets/c50a72f0-58f8-48ed-ae8b-579335794b4a" />
<img width="1919" height="1016" alt="image" src="https://github.com/user-attachments/assets/105aef4c-e050-4bf5-b389-3e0bb09e8e70" />

### ping command :
### Kali Linux:
<img width="1918" height="1017" alt="image" src="https://github.com/user-attachments/assets/0ecfdacd-2c69-4afb-8c1b-07806d1aadd8" />

### Windows:
<img width="1470" height="482" alt="image" src="https://github.com/user-attachments/assets/b36cfbb1-16d2-4c55-9023-a56ab0b1280e" />


### whois :
<img width="1918" height="1022" alt="image" src="https://github.com/user-attachments/assets/e28806bb-f24d-44e9-834e-eadead5649f3" />
<img width="1918" height="327" alt="image" src="https://github.com/user-attachments/assets/eef7415d-d7f8-4845-a442-8ed9183d922f" />

### netcat :
<img width="1917" height="391" alt="image" src="https://github.com/user-attachments/assets/0c598f28-83f9-459d-b231-33efc43d9fbb" />

### nmap :
<img width="1918" height="302" alt="image" src="https://github.com/user-attachments/assets/87919d8f-ab32-40d7-acd3-4dd25951c0f4" />

### whatweb :
<img width="1918" height="192" alt="image" src="https://github.com/user-attachments/assets/238e0829-14b1-485d-bb3c-88c59f9276de" />

### httprint :
<img width="1918" height="907" alt="image" src="https://github.com/user-attachments/assets/1c8ee702-7702-4345-9c1c-31a1f7d06b69" />

### TCP traceroute :
<img width="1918" height="342" alt="image" src="https://github.com/user-attachments/assets/0b82904e-26ea-4f76-b870-9963698d14e0" />

### UDP traceroute :
<img width="1918" height="507" alt="image" src="https://github.com/user-attachments/assets/4f8103d9-fc73-4eeb-8bb2-96b4c6075273" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
