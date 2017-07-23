---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E. in Information Technology, University of Pune, India, 2012
* M.S. in Computer Science, Rutgers University, NJ 2017 (expected)

Work experience
======
* June-Aug 2017: Cloud Software Engineer Intern at Intel Corporation
  * Performed research on NVMe over Fabrics (NVMe-oF) as a scalable Cloud Storage solution
  * Developed a prototype on NVMe-oF with solid state drive to derive a scalable, low latency and high performing Cloud Storage solution in Intel Rack Scale DesignTM data centers
  * Implemented ‘conio’-a command-line tool for automated I/O benchmarking of Docker containers on NVMe volumes using Python. This tool is used by several teams for quick I/O benchmarking of containers
  * Implemented Intel Snap plugin using Go to extract NVMe-based cloud storage telemetry and monitor NVMe Over Fabrics using Docker containers orchestrated by Kubernetes

* July 2012-Mar 2014: Software Engineer at NTT Data Americas
  * Designed and implemented Central Logging System and ‘Backup and Restore’ System of GresCubeTM: a commercial distributed database service which guarantees minimal downtime and enhanced business continuity
  * Architectured six times faster disaster recovery operations module using various file synchronization, archive and transfer utilities upon customer’s demand after the Megaquake of Japan
  * Performed an extensive research on issues with virtualization overhead caused by LXC Containers, KVM and OpenVZ, whose outcome became the foundation of GresCubeTM
  * Analyzed and compared Advance Update feature of distributed databases using LXC Containers and HA services to test servers based on network package flow to allow updates with  minimal downtime
  * Developed Puppet scripts to automate creation of web server components called PROSSIONETM
 
* Sept 2016-Dec 2017: Part Time Lecturer at Rutgers University
  * Constructed, implemented and executed an effective lesson plan for a diverse group of college students
  * Taught logic and thought building techniques for programming using Scratch
  
 
 Skills
======
* Programming:
  * Python, C, Java, Go 
* Virtualization:
  * Libvirt, LXC, KVM 
* Cloud: 
  * Kubernetes, Docker, DevOps, Puppet(1+)
* Database:
  * PostgreSQL(2+)
* Web:
  * HTML, Bootstrap, Web Services 
* Operating System:
  * Linux, Windows 
* Project Management:
  * GitHub, Agile


Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
