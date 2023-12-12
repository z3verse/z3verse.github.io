---
title: Optimizing IoT Web Fuzzing by Firmware Infomation Mining
authors:
- Yifei Gao
- Xu Zhou
- Wei Xie
- Baosheng Wang
- Enze Wang
- Zhenhua Wang
date: '2022-01-01'
publishDate: '2023-12-12T07:33:12.089828Z'
publication_types:
- article-journal
publication: '*Applied Sciences*'
doi: 10.3390/app12136429
abstract: 'IoT web fuzzing is an effective way to detect security flaws in IoT devices.
  However, without enough information of the tested targets, IoT web fuzzing is often
  blind and inefficient. In this paper, we propose to use static analysis to assist
  IoT web fuzzing. Our insight is that plenty of useful information is hidden in firmwares,
  which can be mined by static analysis and used to guide the subsequent dynamic analysis&mdash;fuzzing.
  Hence, our approach contains two stages: pre-fuzzing stage and fuzzing stage. In
  the pre-fuzzing stage, we perform static analysis on the IoT firmwares to exploit
  helpful information, such as web page paths, interfaces, and shared keywords. These
  kinds of information are used to construct diverse seeds for covering more web paths
  and interfaces, and are also used to prioritize seeds according to their importance
  (related to shared keywords) in the fuzzing stage. Based on this approach, we implement
  a prototype IoT web fuzzing system&mdash;IoTParser. Experiments show that IoTParser
  increased the vulnerability discovery capability by 44% on average, while increasing
  the vulnerability discovery efficiency by 48.2% on average compared with state-of-the-art
  IoT web fuzzer. In addition, IoTParser has found 13 vulnerabilities, including 7
  0-day.'
links:
- name: URL
  url: https://www.mdpi.com/2076-3417/12/13/6429
---
