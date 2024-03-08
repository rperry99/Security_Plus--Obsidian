---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
  - TOCTOU
---
# What is a race condition?
- A programming conundrum when things occur at the same time, and its not taken care of by the devs.
	- Something that can be utilized by attackers.

# Time-of-check to Time-of-Use Attack (TOCTOU)
- Check the system
- When do you use the results of your last check?
- Something might happen between the check and it's use.

# Race Condition Diagram
![[Pasted image 20240308125522.png]]

# Real World Examples
- Jan 2004 - Mars Rover "Spirit"
	- It reboots when a problem is identified
	- Problem ins with the file system, so reboot because of the file system problem
	- It gets stuck in a reboot loop because the reboot _is_ the problem.
- GE Energy - The Energy Management System
	- Three power lines failed at the same time
	- Race condition delayed alerts
	- Cause of the Northeast Blackout of 2003
- Therac-25 radiation therapy machine in the 1980s
	- Used software interlocks instead of hardware
	- Race condition caused 100 times the normal does of radiation
	- Six patients were injured, and three were killed.

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
