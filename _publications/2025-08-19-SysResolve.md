---
title: "SysResolve: Study on In-Context LLM Generation of Resolution Scripts"
collection: publications
category: conference
permalink: /publications/fnode
excerpt: "Study on In-Context LLM Generation of Resolution Scripts"
date: 2025-08-19
venue: '<a href="https://www.dexa.org/2025/dexa2025.html" target="_blank">International Conference on Database and Expert Systems Applications</a>Bangkok, Thailand'
layout: single-publication
author_profile: true
authors: "Harsh Borse, <b>Utkalika Satapathy</b>, Mainack Mandal, Bivas Mitra"
# youtube_id: "ANRN3iSy3Qc"
# teaser_video: "https://www.youtube.com/watch?v=ANRN3iSy3Qc"
# code: "https://github.com/usatpath01/MuProv"
# slides: "https://drive.google.com/file/d/example-slides-muprov/view"
# labpage: "https://ubinet-iitkgp.github.io/ubinet/pages/muprov.html"
# paperurl: 'http://usatpath01.github.io/files/urcd-icdcs2024.pdf'
doi: "10.1007/978-3-032-02049-9_10"
venue_short: "Springer DEXA 2025 (Ranked: C)"
detail: "pp. 130--136"
# status: "Best Paper 1st Runner Up Award"   # only when relevant

abstract: "Microservices pose challenges for automated fault resolution due to their distributed and complex nature. We present SysResolve, a framework that automates the entire resolution pipeline by combining multi-modal Root Cause Analysis (RCA) with Large Language Models (LLMs). RCA outputs are converted to natural language and passed through a Retrieval-Augmented Generation (RAG) pipeline to produce executable scripts. We evaluated and experimented on two microservices applications with three LLM (LlaMa3-70B, GPT-4, Claude 3.7). Our analysis highlights significant gains of current LLMs generation power from few-shot learning, with SysResolve achieving expert-level remediation while reducing recovery time."

citation: "Borse, H., Satpathy, U., Mondal, M., & Mitra, B. (2025, August). SysResolve: Study on In-Context LLM Generation of Resolution Scripts. In International Conference on Database and Expert Systems Applications (pp. 130-136). Cham: Springer Nature Switzerland."

contributors:
  - name: "Harsh Borse"
    photo: "http://usatpath01.github.io/images/contributors/rishabh.jpg"
    affiliation: "IIT Kharagpur"
    url: ""
  - name: "Utkalika Satapathy"
    photo: "http://usatpath01.github.io/images/USatapathy.JPG"
    affiliation: "IIIT Bhubaneswar"
    url: "http://usatpath01.github.io"
  - name: "Mainack Mandal"
    photo: "http://usatpath01.github.io/images/contributors/sandip.jpg"
    affiliation: "IIT Kharagpur"
    url: ""
  - name: "Bivas Mitra"
    photo: "http://usatpath01.github.io/images/contributors/sandip.jpg"
    affiliation: "IIT Kharagpur"
    url: ""
---

<!-- ## Overview

μProv - An application-agnostic framework to capture fine-grained system interactions across microservices leveraging eBPF and constructs dynamic runtime provenance graphs representing the causal relationships between system subjects and objects.

## Key Contributions
- **Custom eBPF-based logging solution:** μProv consists of a low-overhead logging solution based on the extended Berkeley Packet Filters (eBPF) designed explicitly for distributed microservice environments.
- **Extracting dynamic provenance graphs:** μProv leverages provenance graphs constructed from low-level system events to detect vulnerabilities while effectively illustrating the causal relationships between processes, file accesses, and network activities, providing a holistic view of system behavior.
- **Vulnerability integration in microservices and dataset generation:** We integrate real-world attack scenarios with known vulnerabilities into our system to evaluate its effectiveness. We have developed “PicShare”, a PoC microservice web application that enables users to upload, view, and receive picture recommendations. -->

## Bibtex
```
@inproceedings{borse2025sysresolve,
  title={SysResolve: Study on In-Context LLM Generation of Resolution Scripts},
  author={Borse, Harsh and Satpathy, Utkalika and Mondal, Mainack and Mitra, Bivas},
  booktitle={International Conference on Database and Expert Systems Applications},
  pages={130--136},
  year={2025},
  organization={Springer}
}
```
