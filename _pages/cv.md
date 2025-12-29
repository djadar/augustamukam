---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<p style="text-decoration:underline;"><a href="https://docs.google.com/document/d/1m4zhpRM_5-rj8YgwfB52hhWrAiGJ3-Iy_BgdmjkH4n4/edit?tab=t.0">Download online CV</a></p>

{% include base_path %}

# Education

## Master of Science in Informatics at Grenoble (MoSiG), Distributed systems, Ensimag

*2021 – 2022*

<u>Relevant Topics</u>: Large scale Data-Management and Distributed systems, Cloud computing, Advanced parallel system, Advanced networking. 

## Master of Engineering in Computer Science, National Advanced School of Engineering of Yaounde

*2016 – 2021*

<u>Relevant Topics</u>: Software engineering and programming, Algorithms, security, Operation research and graph, Machine Learning and Data Mining, Management.


# Professional experience

## Ph.D in Distributed Systems applied to Blockchains, University of Bordeaux

*2022 – 2025*

<u>Main idea</u>: Enhancing tolerance of peer sampling protocols to Byzantine attacks in Blockchains; Finding occurrences of elements in memory-constrained systems in real time. 

My research focuses on designing **Byzantine fault-tolerant peer sampling protocols** to improve the resilience of distributed systems. 

My first contribution is a collaborative protocol that uses SGX-enabled devices to provide a trusted execution environment that enables secure and verifiable collaboration between peers.  
One of the key achievements of this work is a **60% increase in fault tolerance** compared to existing protocols. Even in the presence of an adversary controlling up to **40% of the system nodes**, our approach effectively limits their impact, ensuring robust and reliable operation.  

Scalability is also a key aspect of my research. By using **hash-based techniques** to efficiently track element frequencies, we design new protocols that have the hability to maintain high performance with **minimal memory overhead**, making them well suited for large-scale distributed systems.  

Our overall work contributes to the advancement of secure and efficient peer-to-peer protocols, with potential applications in blockchain networks, decentralised computing and beyond.  

<u>Supervisors</u>: <a href="https://www.reveillere.fr/">Laurent Réveillère</a> and <a href="https://sites.google.com/view/joachim-bruneau-queyreix/">Joachim Bruneau-Queyreix</a>.

<u>Technical tools</u>: g5k, Ansible, EnosLib, Rust, Go, R language

## Intern, Digital Power Team, Schneider Electric, France  

*02/22 – 08/22*

During this internship, I implemented secure storage solutions on Am65xx devices. This involved using TrustZone with OpTEE for secure storages based on the Linux filesystem and RPMB on eMMC. Additionally, I integrated the Trusted Platform Module (TPM) on equipements to enhance the security of cryptographic operations, such as RSA and ECDSA, and to secure TLS communication.

## Research Intern, Laboratoire de l'Informatique du Parallélisme (LIP), ENS Lyon, France

*03/21 – 09/21*

Design of memory buffer protection policies using Intel SubPage Write Protection (SPP). This included identifying the causes of buffer overflows documented over the past 12 years and implementing SPP management functions within the XEN hypervisor.

<u>Supervisors</u>: <a href="https://lig-membres.imag.fr/tchanaa/index.html">Alain TCHANA</a> and <a href="https://sites.google.com/view/stellabi/accueil?authuser=0">Stella BITCHEBE</a>.

## Research Intern, LIP team, ENS Lyon, France

*07/20 – 09/20*

I modified the notification mechanisms within the QEMU-KVM distributed system. Additionally, I defined an ioctl in the KVM hypervisor and implemented a method to transfer data from userspace to kernel space.

<u>Supervisors</u>: <a href="https://lig-membres.imag.fr/tchanaa/index.html">Alain TCHANA</a>

Skills
======

## Programming Languages
**Systems Programming**: Rust, Go, C, C++
**Scripting & Analysis**: Python, R
**Web Development**: JavaScript, HTML, CSS
**Other**: Java, CUDA

## Infrastructure & DevOps
**Distributed Systems**: Grid5000 (g5k), EnosLib, Ansible
**Containerization**: Docker, Kubernetes, Yocto, Kas
**Build Systems**: Meson, Makefile, CMake

## Databases & Tools
**Databases**: MySQL, MariaDB
**Documentation**: LaTeX, Microsoft Office Suite
**Scientific Computing**: MATLAB

## Operating Systems
**Linux**: Ubuntu, Kali Linux
**Windows**: XP, 7, 10

## Methodologies & Modeling
**Development Methodologies**: Scrum, V-cycle
**Modeling Languages**: UML, Merise, PASSI

## Professional Skills
Communication • Proactivity • Discipline • Adaptability • Team Collaboration • Problem-Solving

Awards & Honors
======
* **Best Paper Award** - 22nd International Symposium on Network Computing and Applications (NCA 2024), Bertinoro, Italy
  * Paper: "AUPE: Collaborative Byzantine fault-tolerant peer-sampling"
  * Recognition for outstanding contribution to Byzantine fault-tolerant distributed systems

Certifications
======
* Programming
  * Introduction à la programmation orientée objet (en Java) <a href="https://coursera.org/share/0b71608664e57e5d9b466b7568b9b220">Coursera</a>
* Cloud
  * DevOps Basics for Everyone (IBM CD0115EN)
 <a href="https://courses.edx.org/certificates/72a5629b120744b8a7dbead5be93ef27">edX</a>
  * Introduction to Cloud Infrastructure Technologies (LFS151)
 <a href="https://ti-user-certificates.s3.amazonaws.com/e0df7fbf-a057-42af-8a1f-590912be5460/9dac347d-ef17-4f6f-9198-c4939b3e1e99-augusta-mukam-5f2db8d5-afa0-4620-a850-4cb84bec2d6d-certificate.pdf">The Linux Foundation</a> 

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
* Session chair at <a href="https://sites.google.com/view/wise25-workshop/home">Wise 2025</a>, december 2025

* Session technician at <a href="https://2025.compas-conference.fr/programme/">Compas 2025</a>, june 2025

* 1 hour and half Interview with a group of L3 students from university of Bordeaux, about my research, april 2025

* 1 hour and half Interview with a group of high school students about my research as part of their program to discover the world of research, june 2024
