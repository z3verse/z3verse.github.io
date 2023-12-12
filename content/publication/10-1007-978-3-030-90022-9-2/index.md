---
title: 'XHunter: Understanding XXE Vulnerability via Automatic Analysis'
authors:
- Zhenhua Wang
- Wei Xie
- Jing Tao
- Yong Tang
- Enze Wang
date: '2021-01-01'
publishDate: '2023-12-12T07:33:12.103263Z'
publication_types:
- paper-conference
publication: '*Security and Privacy in Communication Networks*'
abstract: XXE vulnerability is a severe cybersecurity threat. OWASP listed the 10
  most serious web application security risks, and XXE ranked fourth. This vulnerability
  can lead to sensitive information leakage, DoS attacks, and intranet asset discovery.
  Little attention has been given to this problem, and manual work is still needed
  to detect these vulnerabilities. Here, we design a penetration test framework, XHunter,
  to discover and exploit XXE vulnerabilities automatically. XHunter can find the
  call chain that triggers a vulnerability and determine the vulnerability's influence
  scope. Specifically, our work addresses many challenges in the analysis of modern
  web applications, such as object-oriented structures. In addition to detecting vulnerable
  sinks, we find the exploit path automatically. We give each vulnerability a risk
  rating based on the potential impact of the exploits. In this paper, we analyze
  22 real-world web frameworks and find 8 unreported vulnerabilities, 2 of which have
  obtained CVE IDs.
---
