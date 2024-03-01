---
Area: "[[Cyber Security]]"
tags:
  - Note
aliases:
  - pentesting
  - pentest
  - penetration test
---

# What is it?
- Someone having permission to try an go into the system to find vulnerabilities.
- This is similar to [[vulnerability scanning]], except with a pentest, the tester is actively trying to exploit the vulnerabilities, not just find them.
- This is often a compliance mandate. Regular penetration testing needs to be done by a 3rd party.
- The [[National Institute of Standards and Technology (NIST)]] has a technical guide to information security testing and assessment. You can find that here: https://professormesser.com.link/800115
# The Rules of Engagement
- This is an important document that defines the purpose and scope of the penetration test, allowing everyone to be aware of the test parameters.
- It will show the type of testing, and the schedule.
	- Will it be on-site, an internal test, and external test?
	- Will it be during normal working hours, after 6 PM only, etc?
- There are rules that go along with this:
	- The [[IP Address]] ranges
	- Emergency contacts
	- How to handle sensitive information
	- What is in scope and out of scope regarding the devices and applications. 
# How Much Does a Tester Know?
- A tester can go in completely blind (called an Unknown Environment)
- A tester can go in with full knowledge (Known Environment)
- A tester can go in with _some_ knowledge (Partially Known Environment)
	- For a partially known, a tester may only focus on certain systems or applications as well.
# The Goal of Penetration Testing
- The tester is trying to find _and exploit_ any vulnerabilities in the system. 
- This comes with a warning, in that when someone is pentesting, they may accidentally cause a [[Denial of Service]].
- [[Buffer Overflows]] can also cause instability.
- A tester may also end up gaining privilege escalation. 
# The Methods of Pentesting
- [[Password Brute-Force]]
- [[Social Engineering]]
- [[Database Injections]]
- [[Buffer Overflows]]
## What are the steps?
1. Initial exploitation --> The tester gets into the system.
2. The tester tries to do some lateral movement, trying to jump from system to system. 
	1. The inside of a network is relatively unprotected.
3. Once in, you need to make sure there's a way back in.
	1. Testers might set up a [[backdoor]], build user accounts, change or verify default passwords.
4. Testers can pivot.
	1. Testers (or attackers) can then use a vulnerable system as a [[relay]] or [[proxy]].
# What happens after a pentest?
- The tester cleans up
	- They leave the network in its original state
	- Remove any binaries or temporary files
	- Remove any backdoors
	- Delete user accounts created during the test.
- Some testers do [[Bug Bounties]] which is essentially doing pentesting for profit. 

### Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
