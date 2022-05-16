---
title: "Information system"
date: 2021-11-09T12:15:16+02:00
draft: false
author: Clemence
tags:
  - School project
---

## Subject

Having purchased the company ABSTERGO, ANIMUS is looking to integrate their their information system with their own.

## Problem

How to integrate ABSTERGO's information system with that of ANIMUS while ensuring security?

## Achievements

We worked on the security of the information system of the company ABSTERGO which was bought by the company ANIMUS. This information system includes following equipment:
- Two routers: One primary, one secondary, in order to have redundancy.
- Two firewalls: One primary, one secondary, in order to have redundancy.
- Four switches: Two primary, two secondary, in order to have redundancy. The The first two switches refer to the DMZ, and the second ones refer to the intranet.
- A WSUS: Which arrives before the intranet in order to carry out the updates of Windows Server.
- A WEB server: Showcase site which will be present in the DMZ so that it is accessible in public.
- Infrastructure composed of :
  - AD
  - DNS
  - DHCP
  - Monitoring
  - IPX
  - Mail server
  - Data server
  - Application server
  - Mail server
- Backup server composed of the elements mentioned above in order to protect the the infrastructure in case of problems.
- Backup server: To protect the data in case of problems.
- VPN server: To ensure the remote connection

![Infra](/img/projects/system/infra.png)

Thus, we had to put in place the elements mentioned above, while ensuring the integral security of our information system.

## Acquired skills

During this project, thanks to the implementation of many elements, I was able to acquire skills in the following areas:
- AD
- DNS
- DHCP
- Monitoring
- ...