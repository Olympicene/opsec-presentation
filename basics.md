---
theme: gaia
_class: lead
paginate: true

size: 16:9
style: |
    section {
        background-color: #204652;
        color: white;
    }

    section img {
        margin: auto;
    }

    section .images {
        text-align: center;
        margin-top: 75px;
    }

    section .images img {
        margin-right: 50px;
    }

    footer a {
        color: white;
    }
    
    img[alt~="center"] {
      display: block;
      margin: 0 auto;
    }




footer: "[acm.cs.uic.edu](https://lug.cs.uic.edu/)"
marp: true
---

![width:350px](/static/basics/ACM.png)

# SIG Cybersecurity
Intro to Cybersecurity

---

# What is Security?
What do you think security is?

<!-- We all roughly know what the cyber in cybersecurity means, but what about security -->
<p class="images">
    <img src="static/basics/orly.png" height="450"/>
</p>

---
## What is Security
"Security is a property (or more accurately a collection of properties)that hold in a given system under a given set of constraints"


---

## What is Security (cont.)
"Security is a property (or more accurately a collection of properties)that hold in a given system under a given set of constraints"
- System -  anything from hardware, software, firmware, and information being processed, stored, and communicated

- Constraints - define an adversary and their capabilities

---

## What is Security (cont.)

"Security is a property (or more accurately a collection of properties)that hold in a given system under a given set of constraints"
- System -  anything from hardware, software, firmware, and information being processed, stored, and communicated

- Constraints - define an adversary and their capabilities

Alternatively, the measures and cotnrols that ensure these properties.

--- 

# What Systems are we Protecting?
<p class="images">
    <img src="static/basics/tubes.jpg" />
</p>

---

<!-- What are the systems? -->

### System/Computer/Information Security

Not always a clear distinction
- Infrastructure
- Protocols
- Applications
- Hosts/Devices

--- 

### System/Computer/Information Security

Complex interactions
- Internet Protocols/Services
- Distributed Systems
- Web/cloud applications

--- 

### System/Computer/Information Security

Not all of it is technology
- People
- Physical security
<p class="images">
    <img src="static/basics/security.png" />
</p>

---

## What can we do at the Network level?
- Cryptography
- Access Control
- Monitoring
- Protocol
- System Design

<!-- • Cryptography

- Wide range of techniques for enabling secure communication

• Access Control

- Authentication and authorization, firewalls, ...

• Monitoring

- Packet/flow monitoring, intrusion detection, ...

• Rigorous protocol and system design/implementation

- Account for both benign failures and malicious actions
- Data corruption, timeouts, dead hosts, routing problems, ...
Eavesdropping, modification, injection, deletion, replay, ...
- Software bugs in network applications turn into vulnerabilities -->

---

## What is Security (cont.)
"Security is a _property_ (or more accurately a collection of properties) that hold in a given system under a given set of constraints"
- System -  anything from hardware, software, firmware, and information being processed, stored, and communicated

- Constraints - define an adversary and their capabilities

--- 

# What Properties are we Holding?
<p class="images">
    <img src="static/basics/lehman.png" height="350"/>
</p>

---


## Core Principles of Cybersecurity

<!-- Confidentiality - Ensures that sensitive information is only accessible to authorized individuals or systems, preventing unauthorized disclosure. -->
<!-- Integrity - Guarantees that data remains accurate, complete, and unaltered during storage, transmission, and processing, maintaining its reliability and trustworthiness. -->

<!-- Availability/Accessibility - Ensures that systems and resources are accessible and operational when needed, minimizing downtime and disruptions to critical services or functions. -->

<!-- Accountability - Establishes responsibility for actions taken within the system, enabling traceability and accountability for security incidents or breaches. -->

![center width:500px](/static/opsec/CIA.jpg)

---

## Confidentiality
- Property that info is not made available to other unauthorized entities
- In transit / At rest
- Solve with Cryptography
- Content Protection is not enough, Metadata is important

---

## Integrity
- Property has not been changed/destroyed/lost
- Solve with Cryto
- also System Integrity
- Weak auth, vuln software

---

## Availability
- Property is Accessible and usable
- DoS
- saturation/distruption/jamming
- Malware
- ransomware/wipe

---

## Additional Principles
<p class="images">
    <img src="static/basics/big_brother.jpg" height="350"/>
</p>

---

## Authentication
- Identify Who you are
- Different Approaches
- Multi-factor authentication
- Cypto solves it
- Password theft/leak

--- 

## Authorization
- Grant users certain privileges/What they can do
- Access control
- Goal: keep unauthorized users from gaining access resources

---

## Privacy
- The right of a person to interact with their environment and determine the degree to share info about itself

---
## Anonymity
- Stat of not being identifiable within a set of subjects
- Unlink able receiver/ unlinkable sender / both

---
## Challenges of Cybersec
- Think like an attacker
- Reason threats and risks
- Balance security costs/benefits

---

## Threat models
- Who are the adversaries - Motives, Capabilities
- What attacks do you need to prevent
- Limitations

---

## How to think like an attacker
- Weakest link
- Identify assumptions
- Think outside the box
### Practice 
- For every system you interact with think about what it means for it to be secure and imagine how it could be exploited

---
## Threat, Vulnerabilities and Attacks
Whats the Difference?


---
## Threat, Vulnerabilities and Attacks
### Threats 
- all different kinds and origins
### Vulnerability 
- Weakness that makes threat possible


---
## Threat, Vulnerabilities and Attacks

### Attack
- Action that exploits vulnerability and enacts a threat
- Active vs passive
- Insider vs outsider

---

## Threat Actors
- Script kiddies
- Criminals
- Nations

---

## Motives
- Curious
- Political/Social
- Bribed/insiders
- Espionage
- Military
- Money

---

### Threat classification
- Microsoft STRIDE
### Risk Assessment
- Microsoft DREAD

---

## Cost
- Security breaches
- Direct cost
- Indirect cotst
### How likely are these costs
- Probability of attacks/success
- Rational paranoia

---

## Thank you

[1] - https://www.fortinet.com/resources/cyberglossary/operational-security

https://www.cisco.com/c/en/us/products/security/what-is-threat-modeling.html

https://radiumhacker.medium.com/threat-modelling-frameworks-sdl-stride-dread-pasta-93f8ca49504e

Presentation made by Kevin Cordero