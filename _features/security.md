---
title: Security
benefit: Secure
keywords: security
summary: "You data is protected with modern security best practices."
icon: lock
featured: true
order: 2
---

## From the beginning
Security was incorporated into the design of Easy Trips from day one.  With a strong background in consulting and developing applications to meet both Washington State security standards, as well as HIPAA compliance, you can trust that we have your best interests in mind.

## Network
All connections to Easy Trips happen via Secure Socket Layer (SSL).  This means that data is encrypted in transit between you and our servers preventing a man-in-middle attack.

## Authentication
Easy Trips uses an email and password combination for authentication.  If access to your email is secure, access to Easy Trips is secure.

If you are interested in other forms of authentication, such as Active Directory or Two-Factor, please contact us.

## Password Security
Our password strength requirements are based on modern research which asserts that a short, difficult to remember password, can be (and often is) less secure than a longer, easy to remember passwerd.

Additionally, all passwords are stored with the OWIN Authentication standard.  (Contrary to what some people think, *open* cryptographic solutions are actually MORE secure than something hidden.  This is because the solutions have been tried and vetted by security experts.  For an "un-disclosed" solution, a hacker with access to the source code can typically find weaknesses very easily.)


## Hosting
Easy Trips is hosted security on Microsoft Azure's servers, which provides the following benefits:
* Isolation.  Our application is completely separated from all other applications on Azure meaning that the number of "server changes" which can impact it are greatly reduced.  This is generally not true for an in-house hosting solution, or even unmanaged Virtual Machines.

* Internally secure.  Because all communication to and from Easy Trips' databases happen internally on Azure's servers, there is no possibility that a hacker will have access to the sensitive connection strings needed for this connection through any weaknesses in the host.

* 24-hour threat management.  Azure servers are constantly on the lookout for malware, spoofing, and distributed denial-of-service (DDoS) attacks.  Additionally, our DNS is managed by cloudflare which offers their own level of protection.

## Data Access


## Data Retention
Our data is backed up by Azure on a continous basis for point-in-time recovery for any time within the past seven days.  Additional backups are created weekly and stored securely for at least three (3) years.


## Application Security
We are protected against all levels of SQL Injection and cross-site scripting attacks, in additional to our user authentication and authorization policies.
