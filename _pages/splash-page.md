---
title: "Welcome to My Portfolio"
layout: splash
permalink: /splash-page/
date: 2025-05-08T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
    - label: "View My Projects"
      url: "/portfolio/"
    - label: "Download Resume"
      url: "/resume/"
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Welcome to my personal website. I'm Abdullah Badawod, a **Network Security Specialist**. Here you can explore my projects, certifications, and experience in cybersecurity."
intro: 
  - excerpt: 'Welcome to my cybersecurity portfolio! I specialize in **network security**, **penetration testing**, and **vulnerability analysis**. Browse through my projects and feel free to contact me for collaboration.'
feature_row:
  - image_path: /assets/images/firewall-setup.jpg
    alt: "Firewall Configuration"
    title: "Firewall Configuration with pfSense"
    excerpt: "A hands-on project demonstrating how to set up and secure a network using **pfSense**."
    url: "/portfolio/firewall-setup/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/penetration-testing.jpg
    alt: "Penetration Testing"
    title: "Penetration Testing Simulation"
    excerpt: "Using **Kali Linux** and **Metasploit** to test the security of a virtual machine and discover vulnerabilities."
    url: "/portfolio/penetration-testing/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/vulnerability-analysis.jpg
    alt: "Vulnerability Analysis"
    title: "Vulnerability Analysis: Log4Shell"
    excerpt: "A detailed analysis of **Log4Shell** vulnerability, its exploitation, and mitigation strategies."
    url: "/portfolio/vulnerability-analysis/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/snort-setup.jpg
    alt: "Snort IDS"
    title: "Intrusion Detection with Snort"
    excerpt: 'Setting up **Snort** IDS/IPS on a Linux environment to detect and respond to network attacks.'
    url: "/portfolio/snort-setup/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/ms900.jpg
    alt: "MS-900"
    title: "Microsoft Certified: MS-900"
    excerpt: 'Preparing for **Microsoft 365 Fundamentals** certification focusing on cloud services.'
    url: "/certifications/#ms-900"
    btn_label: "Learn More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/ethical-hacking.jpg
    alt: "Ethical Hacking"
    title: "Ethical Hacking & Pen Testing"
    excerpt: 'Hands-on experience in penetration testing, ethical hacking, and securing networks using the latest tools and techniques.'
    url: "/portfolio/ethical-hacking/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}
