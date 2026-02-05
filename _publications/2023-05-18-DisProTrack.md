---
title: "DisProTrack: Distributed Provenance Tracking over Serverless Applications"
collection: publications
permalink: /publication/2023-05-18-DisProTrack
authors: "<b>Utkalika Satapathy</b>, Rishabh Thakur, Subhrendu Chattopadhyay, Sandip Chakraborty"

date: 2023-05-17
venue: '<a href="https://infocom2023.ieee-infocom.org/">IEEE INFOCOM 2023</a>'
paperurl: 'http://usatpath01.github.io/files/disprotrack-infocom2023.pdf'
sourcecode: 'https://github.com/usatpath01/DisProTrack'
slides: 'https://drive.google.com/file/d/example-slides-disprotrack/view'
video: 'https://youtube.com/watch?v=example-disprotrack'

#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<b>Authors</b>: <b>Utkalika Satapathy</b>, Rishabh Thakur, Subhrendu Chattopadhyay, Sandip Chakraborty 

## Overview

Universal Provenance Graph Generation for Serverless Application.

How to detect if a microservice is compromised in a serverless application - DisProTrack comes to the rescue - It generates Universal Provenance Graph (UPG) by combining system logs and application logs together for provenance tracking over serverless architecture.

## Key Features

* **Design of the UPG from application and system logs:** DisProTrack's Static analyzer module generates the application-specific Log Message String-Control Flow Graph (LMS-CFG) from the application binaries which provides a profile of the application.

* **Runtime Execution Unit identification:** DisProTrack has a Linux Loadable Kernel Module (LKM) that can intercept the system calls generated during execution time to identify the semantic relationship between the system logs and the application logs.

* **Improved Search Efficacy:** Instead of storing the raw log messages in the UPG, we propose conversion and storage of an equivalent regular expression. This method improves the matching accuracy of log messages during the investigation phase and reduces the runtime search complexity by providing a faster response time.

* DisProTrack can be deployed as a microservice on top of the SLC without instrumenting the source code of the applications.

* DisProTrack has a minimal memory footprint (~KB) & responds within 20s-30s.

## Contributors

![Author's Name](images/author-image.png)


* **Utkalika Satapathy** - IIT Kharagpur, India
* **Rishabh Thakur** - IIT Kharagpur, India  
* **Subhrendu Chattopadhyay** - IDRBT Hyderabad, India
* **Sandip Chakraborty** - IIT Kharagpur, India

## Links

* <a href="http://usatpath01.github.io/files/disprotrack-infocom2023.pdf" target=_blank><i class="fas fa-file-download"> Download Paper</i></a>

* <a href="https://docs.google.com/presentation/d/1xbSE_v0gd2U_PnjyYjgXmIdGsIKuizC9-TVzmYvWYjU/edit?usp=sharing" target=_blank><i class="fas fa-file-download"> Download Slides</i></a>

* <a href="https://github.com/usatpath01/DisProTrack" target=_blank><i class="fab fa-github-square" style="font-size:18px"> <b>Source Code</b></i></a>

* <a href="https://ubinet-iitkgp.github.io/ubinet/pages/disprotrack.html" target=_blank><i class="fab fa-youtube-square" style="font-size:18px"> <b>Lab Page</b></i></a>

<iframe width="560" height="315" src="https://www.youtube.com/embed/0nJBD3hPIpA?si=sGTBiRg07EfpmDn2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!--Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).-->