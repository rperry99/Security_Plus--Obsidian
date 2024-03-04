---
Area: "[[Cyber Security]]"
tags:
  - Note
aliases:
  - hash
  - hashes
---
# What is it?
- Running data (often a password) through an algorithm to then be represented by a string of text often referred to as a message digest or a fingerprint.
- It's a one-way trip. It's impossible to recover the original message from the digest.
- A common way to store passwords.

# Hash Collisions

^c8c569

- These are very bad.
- It's when two different inputs will end up with the same hash. 
- If this happens, you need to find a new hashing algorithm.

# Make it Salty
- When you store a password, there may also be a [[Salting|salt]] added to it, which is essentially some random extra data so that even if someone share's the same password, the hash won't be the same.

# Hash Example
- [[Secure Hashing Algorithm 256bit (SHA-256)]]
- Used in many applications.

| `Password` | `Hash (Or Message Digest)`                                          |
| ---------- | ------------------------------------------------------------------- |
| 123456     | 8d969eef6ecad3c29a3a629280e686cf0c3f5d5a86afff3ca12020c923adc6c9223 |
| 1234567    | 8bb0vg6rb9b17d0f7d22v456f121257dc1254e1f016965370476383ea776df414   |
| qwerty     | 65e84ve33532fv784c48129675f9eff3a682b27168c0ra744b2cf58ee02337c5156 |
| password   | 5e884898da28047151d0e56f8dc6292773603d0d6aavvdd62a11ef721d1542d8    |
- All password hashes are the same length, but very different. 
- If there is a [[#Hash Collisions|collision]] in the hash, then that hashing algorithm has a vulnerability in it.


---
# Related Notes
```dataview
list
from [[]] and #Note 
sort file.name asc
```
