---
title: "MicroSuggest: Kernel-Aware Microservice Decomposition"
collection: publications
category: conference
permalink: /publications/microsuggest
excerpt: "Kernel-Aware Microservice Decomposition"
date: 2025-08-19
venue: '<a href="https://www.dexa.org/2025/dawak2025.html" target="_blank">27th International Conference on Big Data Analytics and Knowledge Discovery (DaWak)</a>, Bangkok, Thailand'
layout: single-publication
author_profile: true
authors: "Harsh Borse, <b>Utkalika Satapathy</b>, Mainack Mandal, Bivas Mitra"
# youtube_id: "ANRN3iSy3Qc"
# teaser_video: "https://www.youtube.com/watch?v=ANRN3iSy3Qc"
# code: "https://github.com/usatpath01/MuProv"
# slides: "https://drive.google.com/file/d/example-slides-muprov/view"
# labpage: "https://ubinet-iitkgp.github.io/ubinet/pages/muprov.html"
# paperurl: 'http://usatpath01.github.io/files/urcd-icdcs2024.pdf'
doi: "10.1007/978-3-032-02215-8_24"
venue_short: "Springer DaWaK 2025 (Ranked: B)"
detail: "pp. 302--308"
# status: "Best Paper 1st Runner Up Award"   # only when relevant

abstract: "Microservice decomposition typically emphasizes logical or domain-driven boundaries, often overlooking performance bottlenecks from low-level system interactions. We present a system call-aware decomposition method that identifies and separates functions likely to interfere at the kernel level. By defining a collision score based on system call frequency and type, and using a fine-tuned Large Language Model to statically predict syscall behavior, we construct a function interaction graph for clustering. Evaluation on Python-based monoliths shows up to 30% latency reduction and improved scalability compared to traditional approaches, demonstrating the value of kernel-informed microservice design."

citation: "Borse, H., Satpathy, U., Mondal, M., & Mitra, B. (2025, August). MicroSuggest: Kernel-Aware Microservice Decomposition. In International Conference on Big Data Analytics and Knowledge Discovery (pp. 302-308). Cham: Springer Nature Switzerland."

contributors:
  - name: "Harsh Borse"
    photo: "http://usatpath01.github.io/images/contributors/harsh_1.JPG"
    affiliation: "IIT Kharagpur"
    url: ""
  - name: "Utkalika Satapathy"
    photo: "http://usatpath01.github.io/images/USatapathy.JPG"
    affiliation: "IIIT Bhubaneswar"
    url: "http://usatpath01.github.io"
  - name: "Mainack Mandal"
    photo: "http://usatpath01.github.io/images/contributors/mm.jpg"
    affiliation: "IIT Kharagpur"
    url: "https://cse.iitkgp.ac.in/~mainack/"
  - name: "Bivas Mitra"
    photo: "http://usatpath01.github.io/images/contributors/bm.jpg"
    affiliation: "IIT Kharagpur"
    url: "https://cse.iitkgp.ac.in/~bivasm/"
---

<!-- ## Overview

μProv - An application-agnostic framework to capture fine-grained system interactions across microservices leveraging eBPF and constructs dynamic runtime provenance graphs representing the causal relationships between system subjects and objects.

## Key Contributions
- **Custom eBPF-based logging solution:** μProv consists of a low-overhead logging solution based on the extended Berkeley Packet Filters (eBPF) designed explicitly for distributed microservice environments.
- **Extracting dynamic provenance graphs:** μProv leverages provenance graphs constructed from low-level system events to detect vulnerabilities while effectively illustrating the causal relationships between processes, file accesses, and network activities, providing a holistic view of system behavior.
- **Vulnerability integration in microservices and dataset generation:** We integrate real-world attack scenarios with known vulnerabilities into our system to evaluate its effectiveness. We have developed “PicShare”, a PoC microservice web application that enables users to upload, view, and receive picture recommendations. -->

## Bibtex
```
@inproceedings{borse2025microsuggest,
  title={MicroSuggest: Kernel-Aware Microservice Decomposition},
  author={Borse, Harsh and Satpathy, Utkalika and Mondal, Mainack and Mitra, Bivas},
  booktitle={International Conference on Big Data Analytics and Knowledge Discovery},
  pages={302--308},
  year={2025},
  organization={Springer}
}
```
