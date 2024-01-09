---
tags:
  - Lecture
  - PSD
time: 2024-01-01
---
|  Lecture 10 | 
| ------------- |

---
# Continuous Integration

### content 
* 
* 
* 

---
## Integration Hell
* Large changes
* Concurrent coding - merge conflicts

### Fowler
* Fowler 2006 purposes to solve this issue -
	Change management - radical daily commit and merge everyday
		**late integration** - team project example: we have lots of branches with big changes meaning the divergence from main is huge and time consuming in end up.
	Quality assurance - automate build, self-testing
	Deployment - easy for anyone to get latest executable
	
---
## Monitoring & Maintaing
* Project should be compiled from source on production env
* Automated regression test should be complete on production env
* Appropiate static checks (code style conformity) should be performed
	**IF ONE OF THE ABOVE FAIL** - This becomes an incident. It is the top priority for project team to fix this.  
This can be avoided by copying project, make the **dummy merge** create private build if fail make a change and try again until it passes only then should the merged and a public build will be performed.
![[Pasted image 20240109104633.png]]
For feature branching ![[Pasted image 20240109104749.png]]
deters users from making regular commits and changes because of large process.

---
## Staging Environments
It is hard to replicate the production eviroment for testing
* Scale of users to large
* 
---
## CI
![[Pasted image 20240109105215.png]]
Useful image to demonstrate a CI tool such as gitlab runners

---

## Useful lecture resources

