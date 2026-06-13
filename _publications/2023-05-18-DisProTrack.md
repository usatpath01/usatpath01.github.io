---
title: "DisProTrack: Distributed Provenance Tracking over Serverless Applications"
collection: publications
category: conference
permalink: /publications/disprotrack
excerpt: "Distributed provenance tracking over serverless applications."
date: 2023-05-17
venue: '<a href="https://infocom2023.ieee-infocom.org/">IEEE INFOCOM 2023</a>'
layout: single-publication
author_profile: true
authors: "<b>Utkalika Satpathy</b>, Rishabh Thakur, Subhrendu Chattopadhyay, Sandip Chakraborty"
youtube_id: "0nJBD3hPIpA"
teaser_video: "https://youtu.be/0nJBD3hPIpA?si=ZPNyMiZ7j3Oeooe3"
code: "https://github.com/usatpath01/DisProTrack"
slides: "http://usatpath01.github.io/files/disprotrack-infocom2023-slides.pdf"
labpage: "https://ubinet-iitkgp.github.io/ubinet/pages/disprotrack.html"
paperurl: 'http://usatpath01.github.io/files/disprotrack-infocom2023.pdf'
doi: "10.1109/INFOCOM53939.2023.10228884"
venue_short: "IEEE INFOCOM 2023"
detail: "pp. 1-10"
status: "Best Paper Runner-Up"   # only when relevant

abstract: "Provenance tracking has been widely used in the recent literature to debug system vulnerabilities and find the root causes behind faults, errors, or crashes over a running system. However, the existing approaches primarily developed graph-based models for provenance tracking over monolithic applications running directly over the operating system kernel. In contrast, the modern DevOps-based service-oriented architecture relies on distributed platforms, like serverless computing that uses container-based sandboxing over the kernel. Provenance tracking over such a distributed micro-service architecture is challenging, as the application and system logs are generated asynchronously and follow heterogeneous nomenclature and logging formats. This paper develops a novel approach to combining system and micro-services logs together to generate a Universal Provenance Graph (UPG) that can be used for provenance tracking over serverless architecture. We develop a Loadable Kernel Module (LKM) for runtime unit identification over the logs by intercepting the system calls with the help from the control flow graphs over the static application binaries. Finally, we design a regular expression-based log optimization method for reverse query parsing over the generated UPG. A thorough evaluation of the proposed UPG model with different benchmarked serverless applications shows the system's effectiveness."
citation: "Satapathy, U., Thakur, R., Chattopadhyay, S., & Chakraborty, S. (2023, May). Disprotrack: Distributed provenance tracking over serverless applications. In IEEE INFOCOM 2023-IEEE Conference on Computer Communications (pp. 1-10). IEEE."
contributors:
  - name: "Utkalika Satapathy"
    photo: "http://usatpath01.github.io/images/USatapathy.JPG"
    affiliation: "IIIT Bhubaneswar"
    url: "http://usatpath01.github.io"
  - name: "Rishabh Thakur"
    photo: "http://usatpath01.github.io/images/contributors/rishabh.jpg"
    affiliation: "IIT Kharagpur"
    url: ""
  - name: "Subhrendu Chattopadhyay"
    photo: "http://usatpath01.github.io/images/contributors/subhrendu.jpg"
    affiliation: "IDRBT"
    url: "https://www.idrbt.ac.in/dr-subhrendu-chattopadhyay/"
  - name: "Sandip Chakraborty"
    photo: "http://usatpath01.github.io/images/contributors/sandip.jpg"
    affiliation: "IIT Kharagpur"
    url: "https://cse.iitkgp.ac.in/~sandipc/"
---

## Overview

Universal Provenance Graph Generation for Serverless Application.

How to detect if a microservice is compromised in a serverless application - DisProTrack comes to the rescue - It generates Universal Provenance Graph (UPG) by combining system logs and application logs together for provenance tracking over serverless architecture.

## Key Contributions
- **Design of the UPG from application and system logs:** DisProTrack's Static analyzer module generates the application-specific Log Message String-Control Flow Graph (LMS-CFG) from the application binaries which provides a profile of the application.
- **Runtime Execution Unit identification:** DisProTrack has a Linux Loadable Kernel Module (LKM) that can intercept the system calls generated during execution time to identify the semantic relationship between the system logs and the application logs.
- **Improved Search Efficacy:** Instead of storing the raw log messages in the UPG, we propose conversion and storage of an equivalent regular expression. This method improves the matching accuracy of log messages during the investigation phase and reduces the runtime search complexity by providing a faster response time.
- DisProTrack can be deployed as a microservice on top of the SLC without instrumenting the source code of the applications.
- DisProTrack has a minimal memory footprint (~KB) & responds within 20s-30s.

## Bibtex
```
@inproceedings{satapathy2023disprotrack,
  title={Disprotrack: Distributed provenance tracking over serverless applications},
  author={Satapathy, Utkalika and Thakur, Rishabh and Chattopadhyay, Subhrendu and Chakraborty, Sandip},
  booktitle={IEEE INFOCOM 2023-IEEE Conference on Computer Communications},
  pages={1--10},
  year={2023},
  organization={IEEE}
}
```
