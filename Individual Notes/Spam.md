---
Area: "[[Cyber Security]]"
tags:
  - Note
  - SocialEngineering
aliases:
---
# What is it?
- These are unsolicited messages, which can be found via email, forums, etc.
- There is even [[Spam Over Instant Messaging (SPIM)]].
- It can contain various types of content
	- Commercial advertizing
	- Non-commercial proselytizing
	- [[Phishing]] attempts
- It's a significant technology issue that can lead to
	- Security concerns
	- overuse of resources
	- Storage cost increases
	- And the resources it takes to manage the spam.
# [[Mail Gateways]]
- Utilize a mail gateway to stop it before it reaches the user.
- These can be on-site or cloud based
# Identifying the Spam
- Use an [[Allowed List]] which will filter out anything as spam if it is _not_ on that list.
- [[Secure Mail Transfer Protocol (SMTP)]] Standards checking; block anything that doesn't follow [[Request for Comments (RFC)]] standards
- [[Reverse DNS (rDNS)]]; Block emails where the sender's domain doesn't match the [[IP Address]].
- [[Tarpitting]]; Intentionally slowing down the server conversation
- Recipient filtering; Block all email not addressed to a valid recipient email address.

### Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
