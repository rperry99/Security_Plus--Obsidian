---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
  - sidejacking
---
# How the Attacker can get your Session ID
## Header Manipulation / Session Hijacking
- Using a tool like Wireshark or Kismet to gather info on you
- They can then exploit [[Cross Site Scripting (XSS)]] to modify web page headers with tools like Tamper, Firesheep, or Scapy.
- They can then use something like Cookies Manager+, a Firefox add-on to modify your [[Cookies]] and steal your session.

![[Pasted image 20240308115807.png]]

### Preventing Session Hijacking
- Encrypt end-to-end
	- They can't capture your [[Session IDs]] if they can't see it.
	- Additional load on the web server ([[Hypertext Transfer Protocol Secure (HTTPS)|Hypertext Transfer Protocol Secure (HTTPS)]])
- Encrypt end-to-somewhere
	- At least avoid capture over a local wireless network.
	- Use a personal [[Virtual Private Network (VPN)]]

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
