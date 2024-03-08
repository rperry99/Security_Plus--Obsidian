---
Area: "[[Cyber Security]]"
tags:
  - Note
  - AttackTypes
aliases:
---
# What is it? 
- The attacker forces a system to downgrade their security.

# A Real World Example
- 2014 - [[Transport Layer Security (TLS)|TLS]] vulnerability [[Padding Oracle on Downgraded Legacy Encryption (POODLE)|POODLE]]
	- An [[On-Path Attacks|on-path attack]].
	- Forces client to fall back to [[Secure Sockets Layer (SSL)|SSL]] 3.0
	- SSL 3.0 has significant cryptographic vulnerabilities
	- Because of POODLE, modern browsers won't fall back to SSL 3.0


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
