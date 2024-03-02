---
Area: "[[Cyber Security]]"
tags:
  - Note
aliases:
  - fileless virus
---
# What is it?
- A type of virus where it doesn't have any form of application or file that gets installed.
- It runs in the memory ([[Random-Access Memory (RAM)|RAM]]).
- These are very hard to detect.

# The Infection Process
1. User clicks on a malicious website link.
2. Website exploits a Flash / Java / Windows vulnerability.
3. Launches [[PowerShell]] and downloads payload in [[Random-Access Memory (RAM)|RAM]]
4. Runs PowerShell scripts and executables in memory, exfiltrates data, and damages files.
5. Adds an auto-start to the [[Registry]] so that it launches when the computer starts.


### Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
