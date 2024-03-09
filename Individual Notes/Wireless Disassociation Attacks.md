---
Area: "[[Cyber Security]]"
tags:
  - Note
  - NetworkAttacks
aliases:
---
# What is a disassociation Attack?
- It's a type of [[Denial of Service (DoS)|DoS]] attack that causes a device on the network to suddenly disconnect form the network.
- It might appear as you connecting, disconnecting, connecting, disconnecting, etc.
- There isn't much you can do about it.

# How does an attacker do this?
- Attackers will send [[802.11 Management Frames]] to your device.
	- As long as an attacker is sending these, the target device will not be able to connect.
	- Original wireless standards did not add protection for management frames
		- They were sent in the clear, and no authentication or validation were required.

# Protecting against a dissociation. 
- [[Institute of Electrical and Electronics Engineers (IEEE)|IEEE]] has already addressed this problem with [[802.11w]] in July 2014.
	- Some of the important management frames are encrypted.
		- Disassociate, deauthenticate, channel switch announcements, etc.
	- Not everything is encrypted though
		- Beacons, probes, authentication, association
	- [[802.11w]] is required for [[802.11ac]] compliance and will roll out going forward.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
