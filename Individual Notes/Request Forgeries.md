---
Area: "[[Cyber Security]]"
tags:
  - Note
  - ApplicationAttacks
aliases:
  - cross-site requests
  - cross-site request forgery
  - XSRF
  - CSRF
  - one-click attack
  - session riding
  - server-side request forgery
  - server-side request
  - SSRF
---
# What is a Cross-Site Request?
- Websites referencing other websites.
	- You visit ProfessorMesser.com
	- Your browser loads text from the ProfessorMesser.com Server
	- Your browser loads a video from YouTube
	- Your browser loads pictures from Instagram.
- [[Hypertext Markup Language (HTML)|HTML]] on ProfessorMesser.com directs requests from your browser.
	- This is a normal and expected action.
	- Most of these are unauthenticated requests.
# The Client and the Server
- Website pages consist of client-side code and server-side code.
- Client side
	- Renders the page on the screen with [[Hypertext Markup Language (HTML)|HTML]] and JavaScript.
- Server Side
	- Performs requests from the client via [[Hypertext Markup Language (HTML)|HTML]] and [[PHP - Hypertext Preprocessor (PHP)|PHP]].
	- Transfer money from one account to the other
	- Post a video on YouTube.
	- Etc.

# Cross-Site Request Forgery (XSRF) or (CSRF)
- Also referred to as a One-Click attack or session riding.
- Sometimes denoted in shorthand as XSRF or CSRF (pronounced sea surf).
- These take advantage of the trust that a web application has for the user.
	- The webs site trusts your browser.
	- Requests are made without your consent or your knowledge.
	- Attacker posts a Facebook status on your account. 
- This is considered a significant web application development oversight.
	- The application should have anti-forgery techniques added.
	- Usually a cryptographic token is added to prevent a forgery. 
![[Pasted image 20240308121412.png]]

# Server-Side Request Forgery (SSRF)
- An attacker finds a vulnerable web application.
	- Send a request to a web server
	- The web server performs the request on behalf of the attacker.
- This is caused by bad programming
	- Never trust the user input
	- Server should validate the input and the responses.
	- There are rare, but can be critical vulnerabilities. 
![[Pasted image 20240308121648.png]]

---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
