---
tags:
  - "#CyberSec"
  - Lecture
time: 2024-01-09
---
|  Lecture 1 | 
| ------------- |

---
# Introduction to CyberSec 

### content 
* What is CyberSec - examples
* Impacts
* Challenges
* Threats
* Design

---
## What is CyberSec

### Why?
To protect targets - aka assets
- Servers
- User devices
- Networks
- ...
	**Anything digital**
### Examples
* DOS - becomes unavailable to network in attended way
* DNS Attacks:
	* DNS amplification 
	* Cache poisoning
	* DNS tunnelling
- Software vulnerabilities:
	- OS command injection
	- SQL injection
	- Cross-site scripting
- Malware
	- Viruses
	- Worms
	- Trojans
	- Rootkits
### Protection
* Anti-malware software
* Firewalls
* Intrusion detection systems - network/gateway stuff?
* Cryptography
* User education and awareness
### Objectives
* Confidentiality
	* Data is safe and accessible to users without access rights. Users given control over there data (privacy)
* Integrity
	* information and programs change data only in the specified and an authorised manner
* Availability
	* System work promptly for authorised users

Additional but not mentioned is because absolute security is not achievable!
**Accountability** - upon an attack, logs and audits to quickly and accurately see why. 

---
## Impacts
**Low impact**
- system can still perform primary functions but effectiveness is noticeably reduced.
- minor damage to assets 
- minor financial loss
- minor harm to individuals
**Medium impact**
- system can still perform primary functions but effectiveness is significant reduced.
- significant damage to assets
- significant financial loss
- minor harm to individuals
**High impact**
* system cannot perform one or more primary functions
* major damage to assets
* major financial loss
* severe or catastrophic harm to individuals


---
## Challenges
* Always considering potential attacks
* Security mechanism is complex and it's not always apparent that issues aren't addressed 
* mechanism are multi-variable and so one shoe doesn't fit all
* attackers need only one weakness and developers need to account for all
* strong security often seen as impairing and non-efficient for users

---
## Threats
**Passive attacks**
* eavesdropping - attempts to learn or make use of information without affecting system resources 
**Active attacks**
* man in the middle - attempts to alter system resources and affect operation
**Inside and Outside Attackers**
* Inside attacker - someone inside the company or network 
* Outside attacker - internet users breaching system, hacker, terrorist, criminal etc.

### Counter Measure


---
## Design
### Economy of Mechanism
Security for hardware and software should be as simple and small possible
* Small design is easier to justify and test
* Complex will make more vulnerabilities - a large rope in constant use will get knotted more easily than small
* Updating becomes easier
Open Design
* Cryptographic algs should be public, nothing secret means it is safe
* public algorithms can be reviewed more easily making them more secure.
Privilege
- Users should have the least amount of access they need
Psychological acceptability
- They should not overly hinder usability - they will then turn it off
Isolation
- systems and services should be used only when necessary.


## Attack surface
Attack vector - an acces and way for attack
attack surfaces 

---
## Useful lecture resources
---