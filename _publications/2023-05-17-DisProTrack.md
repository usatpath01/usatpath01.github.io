---
title: "DisProTrack: Distributed Provenance Tracking over Serverless Applications"
collection: publications
permalink: /publication/2023-05-17-DisProTrack
authors: "<b>Utkalika Satapathy</b>, Rishabh Thakur, Subhrendu Chattopadhyay, Sandip Chakraborty"
excerpt: '<div style="text-align: justify">Provenance tracking has been widely used in the recent literature to debug system vulnerabilities and find the root causes behind faults, errors, or crashes over a running system. However, the existing approaches primarily developed graph-based models for provenance tracking over monolithic applications running directly over the operating system kernel. In contrast, the modern DevOps-based service-oriented architecture relies on distributed platforms, like serverless computing that uses container-based sandboxing over the kernel. Provenance tracking over such a distributed micro-service architecture is challenging, as the application and system logs are generated asynchronously and follow heterogeneous nomenclature and logging formats. This paper develops a novel approach to combining system and micro- services logs together to generate a Universal Provenance Graph (UPG) that can be used for provenance tracking over serverless architecture. We develop a Loadable Kernel Module (LKM) for runtime unit identification over the logs by intercepting the system calls with the help from the control flow graphs over the static application binaries. Finally, we design a regular expression-based log optimization method for reverse query parsing over the generated UPG. A thorough evaluation of the proposed UPG model with different benchmarked serverless applications shows the system’s effectiveness.</div>'
date: 2023-05-17
venue: '<a href="https://infocom2023.ieee-infocom.org/">IEEE INFOCOM 2023</a>'
paperurl: 'http://usatpath01.github.io/files/disprotrack-infocom2023.pdf'
#citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
<div style="text-align: justify">
Provenance tracking has been widely used in the recent literature to debug system vulnerabilities and find the root causes behind faults, errors, or crashes over a running system. However, the existing approaches primarily developed graph-based models for provenance tracking over monolithic applications running directly over the operating system kernel. In contrast, the modern DevOps-based service-oriented architecture relies on distributed platforms, like serverless computing that uses container-based sandboxing over the kernel. Provenance tracking over such a distributed micro-service architecture is challenging, as the application and system logs are generated asynchronously and follow heterogeneous nomenclature and logging formats. This paper develops a novel approach to combining system and micro- services logs together to generate a Universal Provenance Graph (UPG) that can be used for provenance tracking over serverless architecture. We develop a Loadable Kernel Module (LKM) for runtime unit identification over the logs by intercepting the system calls with the help from the control flow graphs over the static application binaries. Finally, we design a regular expression-based log optimization method for reverse query parsing over the generated UPG. A thorough evaluation of the proposed UPG model with different benchmarked serverless applications shows the system’s effectiveness.
</div>

<b>Authors</b>: <b>Utkalika Satapathy</b>, Rishabh Thakur, Subhrendu Chattopadhyay, Sandip Chakraborty 
<br><br>
<a href="http://usatpath01.github.io/files/disprotrack-infocom2023.pdf" target=_blank><i class="fas fa-file-download"> Download Paper</i></a>

<a href="https://github.com/usatpath01/DisProTrack" target=_blank><i class="fab fa-github-square" style="font-size:18px"> <b>Source Code</b></i></a>
<!--Recommended citation: Your Name, You. (2009). "Paper Title Number 1." <i>Journal 1</i>. 1(1).-->