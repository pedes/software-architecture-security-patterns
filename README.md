# Software Architecture Security Patterns (Best Practices)

---

## Introduction
This repository contains a collection of security-related practices and patterns that could be applied to a software solution. The guidelines provided here are a collection from past experiences, books, seminars, etc. and it never intends to replace a proper discussion and architectural decisions taking with the context in mind.


## Why does secuirty matters?

Security must be addressed as a concern, and not as a feature. For example, having a login page is a feature, but the concern addressed here is the confidentialy that the information has, and every user should only be able to see/access its own data/info. To get real security, you need to get away from the mindset of seeing security as a set of features, instead as a concern that cuts across the functionality.
  
  Categories of security concerns:
  - Confidentiality
  - Integrity
  - Availability
  - Traceability

## Secure by design
Writing good and secure software is not a trivial task, therefore, a best way to deal with the need of having security in place is to include it into the design of the software and the tools that we use to build it.

Design, can be seen as any activity or decision taken during the development of the software. Security must be one of those decisions and part of the design, and **everyone** involved in the development process should be trained in software security. For instance:
- Developers should know about OWASP Top 10
- QA/Testers should be trained in basic penetration testing techniques
- Business analyst should be capable of having discussions about software security

It's important to include security while designing the software solution, otherwise, adding security later it might not be possible if the security aspects needed imply a fundamentally different design. e.g. it's usually very hard (or even impossible) to add scalability/statelessness late in the software development cycle.

 

