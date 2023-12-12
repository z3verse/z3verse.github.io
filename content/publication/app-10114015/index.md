---
title: 'EWVHunter: Grey-Box Fuzzing with Knowledge Guide on Embedded Web Front-Ends'
authors:
- Enze Wang
- Baosheng Wang
- Wei Xie
- Zhenhua Wang
- Zhenhao Luo
- Tai Yue
date: '2020-01-01'
publishDate: '2023-12-12T07:33:12.109902Z'
publication_types:
- article-journal
publication: '*Applied Sciences*'
doi: 10.3390/app10114015
abstract: 'At present, embedded devices have become a part of people&rsquo;s lives,
  so detecting security vulnerabilities contained in devices becomes imperative. There
  are three challenges in detecting embedded device vulnerabilities: (1) Most network
  protocols are stateful; (2) the communication between the web front-end and the
  device is encrypted or encoded; and (3) the conditional constraints of programs
  in the device reduce the depth and breadth of fuzz testing. To address these challenges,
  we propose a new type of gray-box fuzz testing framework in this paper, called EWVHunter,
  which is mainly used to find authentication bypass and command injection vulnerabilities
  in embedded devices. The key idea in this paper is based on the observation that
  most embedded devices are controlled through the web front-end. Such embedded devices
  often contain rich information in the communication protocol between the web front-end
  and device. Therefore, by filling data at the input source on the web front-end
  and reusing web front-end program logic, we can effectively solve the impact of
  the stateful network protocol and communication data encryption on fuzzing without
  relying on any knowledge about the communication protocol. Additionally, we use
  firmware information extraction to enhance EWVHunter so that it can detect vulnerabilities
  in deep layer codes and hidden interfaces. In our research, we implemented EWVHunter
  and evaluated 8 real-world embedded devices, and our approach identified 12 vulnerabilities
  (including 7 zero-days), which affect a total of 31,996 online devices.'
links:
- name: URL
  url: https://www.mdpi.com/2076-3417/10/11/4015
---
