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

Ph.D in Distributed Systems applied to Blockchains, University of Bordeaux
------ 

*2022-2025 (ongoing)*

Main idea: Enhancing tolerance of peer sampling protocols to Byzantine attacks in Blockchains

Master of Science in Informatics at Grenoble(MoSiG), Distributed systems, Ensimag
------

*2021-2022*

Relevant Topics: Distributed systems, Cloud computing 

Engineer Degree Dimploma, National Advanced School of Engineering of Yaounde, Department of Computer Science, 2021
------

*2016-2021*

Relevant Topics: Programming, Algorithms, security


Professional experience
======

Intern, Digital Power Team, Schneider Electric, France
------ 

*02/22 - 08/22*

During this internship, I implemented secure storage solutions on Am65xx devices. This involved using TrustZone with OpTEE for secure storages based on the Linux filesystem and RPMB on eMMC. Additionally, I integrated the Trusted Platform Module (TPM) on equipements to enhance the security of cryptographic operations, such as RSA and ECDSA, and to secure TLS communication.

Research Intern, LIP team, ENS Lyon, France
------ 

*03/21 - 09/21*

Design of memory buffer protection policies using Intel SubPage Write Protection (SPP). This included identifying the causes of buffer overflows documented over the past 12 years and implementing SPP management functions within the XEN hypervisor.

Research Intern, LIP team, ENS Lyon, France
------ 

*07/20 - 09/20*

I modified the notification mechanisms within the QEMU-KVM distributed system. Additionally, I defined an ioctl in the KVM hypervisor and implemented a method to transfer data from userspace to kernel space.

Skills
======
* Programming
  * Rust, Go, C , Python, C++, Java, JavaScript, HTML, CSS, Cuda, R

* IT 
  * MATLAB, Microsoft office tools, Latex;   MySQL, MariaDB 
  * Linux: Ubuntu, Kali Linux; Windows:  XP,7,10;   
  * Yocto, Kas, Meson, Makefile, CMake

* Professional and personal skills
  * Scrum and V-cycle methodologies 
  * Merise, UML, PASSI modeling
  * Communication, Proactivity, Discipline, Positivity, Adaptability, Focus


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* 1 hour and half Interview with a group of high school students about my research as part of their program to discover the world of research, june 2024