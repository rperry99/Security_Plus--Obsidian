---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
  - HTTP Downgrade
---
# What is SSL Stripping?
- Also referred to as HTTP Downgrade.
- It combines an [[On-Path Attacks|on-path attack]] with a [[Downgrade Attacks|downgrade attack]].
- The attacker must sit in the middle of the conversation.
	- Must modify the data between the victim and web server using a [[Proxy Server]], [[ARP Spoofing]], [[Rogue Access Points]], etc.
- The victim does not see any significant problems except the browser page isn't encrypted.
	- It strips away the S in [[Hypertext Transfer Protocol Secure (HTTPS)|HTTPS]]. (Considered the HTTP Downgrade).
- A client and server problem that works on both [[Secure Sockets Layer (SSL)|SSL]] and [[Transport Layer Security (TLS)|TLS]].

![[Pasted image 20240308124855.png]]


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
