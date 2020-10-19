# Software Architecture Security Patterns (Best Practices)

---

## Introduction
This repository contains a collection of security-related practices and patterns that could be applied to a software solution. The guidelines provided here are a collection from past experiences, books, seminars, etc. and it never intends to replace a proper discussion and architectural decisions taking with the context in mind.


## Why does secuirty matters?
- Security must be addressed as a concern, and not as a feature. For example, having a login page is a feature, but the concern addressed here is the confidentialy that the information has, and every user should only be able to see/access its own data/info. To get real security, you need to get away from the mindset of seeing security as a set of features, instead as a concern that cuts across the functionality.
  Categories of security concerns:
  - Confidentiality
  - Integrity
  - Availability
  - Traceability

## Secure by design
Writing good and secure software is not a trivial task, therefore, a best way to deal with the need of having security in place is to include it into the design of the software and the tools that we use to build it.
