---
title: "Operating System"
collection: courses
type: "Undergraduate Course"
permalink: /courses/2026-autumn-OS
venue: "Department of Computer Science, IIIT Bhubaneswar"
date: 2026-07-27
location: "India"
semester: "Autumn 2026"
credits: 4
duration: "40 Hours"
level: "Undergraduate"
layout: single-course

overview: "A comprehensive introduction to the principles, techniques and structure of operating systems — covering OS support for concurrency (threads) and synchronization, resource management (CPU, memory, I/O), and distributed services."

facts:
  - { label: "Instructor", value: "Utkalika Satapathy" }
  - { label: "Duration", value: "40 Hours" }
  - { label: "Credits", value: "4" }
  - { label: "Prerequisite", value: "Data structures, Basics of Computer Organization, High-level Programming Language (C or JAVA), Basic knowledge of Computer Hardware and System Software" }

schedule:
  - { date: "Wk 1", topic: "Foundations: Introduction to Operating Systems", slides: "https://drive.google.com/file/d/1hhqjFMbbmgwIyRpajdflHcwbDI4hZ1Nn/view?usp=sharing" }
  - { date: "Wk 2", topic: "Foundations: Computer Organization", slides: "https://drive.google.com/file/d/1TFDNrZZD0ZsYuLbpwixfHA6ecrIztu7e/view?usp=sharing" }  
  - { date: "Wk 3", topic: "Foundations: OS Structures & System Calls", slides: "TBU" }
  - { date: "Wk 3", topic: "Basics of Process, Thread and IPC", slides: "TBU" }
  - { date: "Wk 4", topic: "Process Scheduling", slides: "TBU" }
  - { date: "Wk 6", topic: "Process Synchronization", slides: "TBU" }
  - { date: "Wk 7", topic: "Process Synchronization & Deadlock", slides: "TBU" }
  - { date: "Wk 8", topic: "Memory Management", slides: "TBU" }
  - { date: "Wk 9", topic: "Virtual Memory", slides: "TBU" }
  - { date: "Wk 10", topic: "Storage & I/O", slides: "TBU" }
  - { date: "Wk 11", topic: "File Systems", slides: "TBU" }

materials:
  - heading: "Syllabus"
    items:
      - { title: "Course Syllabus", url: "https://drive.google.com/file/d/1S3u1M7QdskF7p_lGrqV8zcow6R8zpZKP/view?usp=sharing", icon: "fa-file-lines" }

textbooks:
  - { title: "Silberschatz, Galvin, Gagne — Operating System Concepts, 10th Ed.", url: "https://drive.google.com/file/d/1AYujIINajm5RovYopxHpmOnHvCvQemVT/view?usp=sharing" }
  - { title: "William Stallings — Operating Systems: Internals & Design Principles, 6th Ed.", url: "https://drive.google.com/file/d/1m48K3Uwg574pLnxlbwNRmeDK7JmWYScT/view?usp=sharing" }
  - { title: "A. S. Tanenbaum — Modern Operating Systems, 3rd Ed.", url: "https://drive.google.com/file/d/1-UXPh-kRdgWBqrz7jo1n7zrhVUjvTkJA/view?usp=sharing" }
  - { title: "Tanenbaum, Woodhull — OS Design & Implementation, 3rd Ed.", url: "https://drive.google.com/file/d/1oQnpW3a_l8eZjF4424avraqaq9PnfGWv/view?usp=sharing" }
  - { title: "Arpaci-Dusseau — Operating Systems: Three Easy Pieces", url: "https://drive.google.com/file/d/1Tja2wdKt8Uz1hGRpCbpzIYyYS_DYv01n/view" }

grading:
  - { item: "Quizzes", weight: 15 }
  - { item: "Mid-Sem Exam", weight: 30 }
  - { item: "End-Sem Exam", weight: 50 }
  - { item: "Teacher's Assessment", weight: 5 }

lab:
  overview: "This lab complements the operating system course. Students will gain practical experience with designing and implementing concepts of operating systems such as system calls, CPU scheduling, process management, memory management, and deadlock handling using C/C++ language in Linux environment."
  materials:
    - heading: "Lab Materials"
      items:
        - { title: "Lab Manual", url: "https://docs.google.com/document/d/1JnA_OwebsK5NsExOLi2dIcm7nmBC4N-zRrE3xuFjezA/edit?usp=sharing", icon: "fa-flask" }
        - { title: "Introduction to Linux", url: "https://drive.google.com/file/d/1YxxKINJNsfXb-AQaM70U3j8ZnTwtN0DL/view?usp=sharing", icon: "fa-file-powerpoint" }
  references:
    - { title: "UNIX: Concepts and Applications, 4th Edition — Sumitabha Das", url: "https://drive.google.com/file/d/1q3wHKFYCwhP_aKmRk0-domaYJAFKIOAR/view?usp=sharing" }
    - { title: "Linux Kernel Development, 3rd Edition — Robert Love", url: "https://drive.google.com/file/d/1U0DUIkhoAEPw712OPFmUB9_VYyCQWDs7/view?usp=sharing" }
    - { title: "The Design of the UNIX Operating System — Maurice J. Bach", url: "https://drive.google.com/file/d/18FZdX0yF8V4L8X01gjs8badjWxYzX7N6/view?usp=sharing" }
    - { title: "Operating Systems: Three Easy Pieces — Remzi H. Arpaci-Dusseau and Andrea C. Arpaci-Dusseau", url: "https://drive.google.com/file/d/1Tja2wdKt8Uz1hGRpCbpzIYyYS_DYv01n/view?usp=sharing" }
    - { title: "Linux: The Complete Reference, Sixth Edition — Richard Petersen", url: "https://drive.google.com/file/d/1FCnQputexxm6DDqszw4XTpQStLudgCoa/view?usp=sharing" }
    - { title: "PThreads Programming — D Buttlar", url: "https://drive.google.com/file/d/1S6GGX_M6RbsTwBdDk7tYYuRIbNhYAIvl/view?usp=sharing" }
    - { title: "Mastering C++ Multithreading — Maya Posch", url: "https://drive.google.com/file/d/1vyCi-GDrJjl-O4O67OZbmJOxD23RbtLE/view?usp=sharing" }

  grading:
    - { item: "Lab Sessions", weight: 70 }
    - { item: "Lab Assessment/Viva", weight: 30 }

---
