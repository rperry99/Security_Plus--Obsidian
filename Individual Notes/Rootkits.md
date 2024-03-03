---
Area: "[[Cyber Security]]"
tags:
  - Note
  - AttackTypes
aliases:
  - rootkit
---
# What is it?
- Originally a [[Unix]] technique that turned into a form of [[Malware]] installed directly on the root of a [[Kernels|kernel]] that's meant to be invisible and next to impossible to remove.
- It modifies the core system files., and can be invisible to the [[Operating System (OS)|OS]] to the point where even a task manager cannot see it.
	- It's also typically invisible to [[Anti-Virus (AV)|anti-virus]] as well.

# Finding and Removing Rootkits
- Look for the unusual, typically you can use an [[Anti-Malware]] scan.
- There are removers that are specific to the rootkit, usually built after the rootkit is discovered.
- You can use a secure boot using [[Unified Extensible Firmware Interface (UEFI))|UEFI]], which is essentially security in the [[Basic Input Output System (BIOS)|BIOS]].


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
