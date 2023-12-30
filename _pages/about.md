---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

[//]: # (# 🥷 About Me 📖 📝 📧 🖖)

I am **Jiaming Wen (文嘉明)**, currently pursuing my Ph.D. at [Wuhan University (WHU)](https://whu.edu.cn/), with a concurrent Joint Ph.D. Program at the [University of Wollongong (UOW)](http://uow.edu.au/). I am working on cryptography and cyber security, to be more specific:
- Recently, my passion lies in analyzing and designing various signature schemes and zero-knowledge protocols based on quantum-resistant assumptions, e.g., Lattice, Multivariate, and Code.
- In the long term, I hope using technologies to establish trust among individuals at almost zero cost, which I consider to be the most subtle and great aspect of cryptography.

Feel free to reach me via <cryptowjm@163.com> (preferred) or <wenjm@whu.edu.cn>, if questions or we share common tastes.

# 📰 News
- <font color=Red>2023/12: I moved to AU to begin a new journey. Thanks to whoever assisted me and the China Scholarship Council (CSC).</font>
[//]: # (- 2023/10: My coauthors and I got two papers rejected )
- 2023/10: My first submission to the [Journal of WoCrypt](https://documents.uow.edu.au/~fuchun/jow.html) was accepted by the Editor-in-Chieeeeeeeeeeeeef after revisions. See the bottom of this page and [the Publisher's website](https://documents.uow.edu.au/~fuchun/methodology.html).
- 2023/09: Finally, I got this homepage done.

# 🏃 Experiences
- 2020/09 - Now: **Ph.D. Candidate in Cryptography**
  <div style="font-size:18px"><span style="float:right">Wuhan, Hubei, China</span><a href="https://cse.whu.edu.cn/" title="School of Cyber Science and Engineering (SCSE), Wuhan University"> School of Cyber Science and Engineering (SCSE), Wuhan University</a> </div>
  Supervisor: [Huanguo Zhang](https://jiamiwen.github.io/documents/Zhang.pdf)

- 2023/12 - 2025/03 (expected): **Joint Ph.D. Program in Cryptography, funded by the [CSC State Scholarship](https://www.csc.edu.cn/chuguo)**
  <div style="font-size:18px"><span style="float:right">Keiraville, NSW, Australia</span><a href="https://www.uow.edu.au/engineering-information-sciences/schools-entities/scit/" title="School of Computing and Information Technology (SCIT), University of Wollongong"> School of Computing and Information Technology (SCIT), University of Wollongong</a> </div>
  Supervisors: [Willy ](https://scholars.uow.edu.au/willy-susilo)[Susilo](https://sites.google.com/view/willy-susilo), [Fuchun ](https://scholars.uow.edu.au/fuchun-guo)[Guo](https://documents.uow.edu.au/~fuchun/), and [Khoa ](https://scholars.uow.edu.au/khoa-nguyen)[Nguyen](https://sites.google.com/view/khoantt/home)

- 2016/09 - 2020/06: **B.S. in Mathematics**
  <div style="font-size:18px"><span style="float:right">Wuhan, Hubei, China</span><a href="http://maths.whu.edu.cn/" title="School of Mathematics and Statistics (SMATHS), Wuhan University"> School of Mathematics and Statistics (SMATHS), Wuhan University</a> </div>

# 📜 Publications
Roughly, my existing publications can be categorized into Post-quantum (Lattice, Multivariate), and Pre-quantum (DL, Pairing). Most of them are irrigations and not worth reading. I have also been looking forward and trying my best to dominate works that please me. Unfortunately, they have been rejected until now.
## Lattice
- [WBY+23] [LaRRS: Lattice-Based Revocable Ring Signature and its application for VANETs](https://ieeexplore.ieee.org/document/10219003)
  <br> **Jiaming Wen**, Lu Bai, Zhichao Yang, Huanguo Zhang, Houzhen Wang, and Debiao He
  <br> *IEEE Transactions on Vehicular Technology (T-VT) 2023* [[Journal](https://vtsociety.org/publication/ieee-transactions-vehicular-technology), JCR Q1, [slides](https://jiamiwen.github.io/documents/larrs-slides.pdf)]
  
- [WWLZ22] [Aitps: A Two-Party Signature Scheme from Asymmetry Module Lattice Problems](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202220533) (in Chinese)
  <br> **Jiaming Wen**, Houzhen Wang, Jinhui Liu, and Huanguo Zhang
  <br> *Journal of Computer Research and Development (计算机研究与发展) 2023* [[Journal](https://crad.ict.ac.cn/), [Chinese CCF-T1](https://www.ccf.org.cn/ccftjgjxskwml/), [slides](https://jiamiwen.github.io/documents/aitps-slides.pdf)]
  
- [LWZ+23] [A post quantum secure multi-party collaborative signature with deterability in the Industrial Internet of Things](https://www.sciencedirect.com/science/article/pii/S0167739X22003983?via%3Dihub)
  <br> Jinhui Liu, **Jiaming Wen**, Bowen Zhang, Shunyu Dong, Bo Tang, and Yong Yu
  <br> *Future Generation Computer Systems (FGCS) 2023* [[Journal](https://www.sciencedirect.com/journal/future-generation-computer-systems), JCR Q1]

- [AWBW23] [Spatial optimization for CRYSTALS-Dilithium Digital Signature Scheme](http://xblx.whu.edu.cn/zh/article/doi/10.14188/j.1671-8836.2022.0199/) (in Chinese)
  <br> Sifan Ao, Houzhen Wang, Lu Bai, **Jiaming Wen**, and Huanguo Zhang
  <br> *Journal of Wuhan University (武汉大学学报) 2023* [[Journal](http://xblx.whu.edu.cn/), Chinese Core]

## Multivariate
- [WWZ23] [Post-quantum Sigma Protocols and Signatures from Low-Rank Matrix Completions](https://link.springer.com/chapter/10.1007/978-3-031-45513-1_11)
  <br> **Jiaming Wen**, Houzhen Wang, and Huanguo Zhang
  <br> *ProvSec 2023* [[Conference](https://provsec2023.github.io/ProvSec2023/#), [CACR-C](https://www.cacrnet.org.cn/site/content/1290.html), [slides](https://jiamiwen.github.io/documents/lrmc-slides.pdf)]

  
## Pre-quantum
- [WWLZ23] [ACKE: Asymmetric Computing Key Exchange Protocol for IoT Environments](https://ieeexplore.ieee.org/document/10131978)
  <br> Houzhen Wang, **Jiaming Wen**✉️, Jinhui Liu, and Huanguo Zhang (First Author is my co-advisor & Corresponding Author)
  <br> *IEEE Internet of Things Journal (IoT-J) 2023* [[Journal](https://ieee-iotj.org/), JCR Q1]

- [LDW+23] [TBSCrowd: A Blockchain Assisted Privacy-Preserving Mobile Crowdsourcing Scheme from Threshold Blind Signature](https://ieeexplore.ieee.org/document/10354463)
  <br> Jinhui Liu, Shunyu Dong, **Jiaming Wen**, Bo Tang, and Yong Yu
  <br> *IEEE Internet of Things Journal (IoT-J) 2023* [[Journal](https://ieee-iotj.org/), JCR Q1]


[//]: # (# 🎖 Selected Honors and Awards)

# 💻 Services
## Teaching
- 2023/02 - 2023/06: **Teaching Assistant**
  <br>Programming Design and Experiment (undergraduate course in Spring 2023), SCSE, Wuhan University
- 2021/09 - 2022/01: **Teaching Assistant**
  <br>Cryptography (undergraduate course in Fall 2021), SCSE, Wuhan University

## Serving as Reviewer
- Journals: *IEEE Internet of Things Journal (IoT-J)*, *IEEE Systems Journal*, *Journal of Information Security and Applications (JISA)*, et al.
- Conferences: *Inscrypt 2023*, et al.

# 🧰 Misc
## Serendipity
My name starts with "jiami" (Chinese for "encrypt"), and ends with "mingwen" (Chinese for "plaintext"). 
<br>I remove "ng" from it to obtain "miwen" (Chinese for "ciphertext") for several usernames of mine, e.g., [wechat](https://jiamiwen.github.io/images/wechat.jpg), twitter, and github, as I believe it is more suitable for spreading over the public channel :-)
## Some useful links
- [My bilibili space](https://space.bilibili.com/59630141), including several talks/courses I am or was interested in.
- [IACR ePrint Archive](https://eprint.iacr.org/), a mysterious website suggested visiting every day.
- [The Lattice Club](https://thelatticeclub.com/), including so many resources about Lattice-based Cryptography.
- [Post-Quantum Signatures Zoo](https://pqshield.github.io/nist-sigs-zoo/), including an overview of Post-Quantum Signatures.
- [Keita Xagawa's Homepage](https://xagawa.net/), including Bibliography on Lattice-based/Code-based Cryptosystems.
- [Kai-Min Chung's Homepage](https://homepage.iis.sinica.edu.tw/~kmchung/), including high-quality cryptography courses in Chinese.
- [Journal of WoCrypt](https://documents.uow.edu.au/~fuchun/jow.html), a very serious fake journal, whose outcomes include ["安全归约导论"](https://documents.uow.edu.au/~fuchun/book.html), ["数字签名密史"](https://documents.uow.edu.au/~fuchun/cryptologic-history.html) and its [slides](https://documents.uow.edu.au/~fuchun/methodology.html). Here are my always-unfinished [notes for the former](https://jiamiwen.github.io/documents/notes.pdf) and [xmind for the latter](https://jiamiwen.github.io/documents/xmind.pdf), which I hope are salutes to Prof. Guo. 


[//]: # (# 💬 Invited Talks)
[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )
[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/))


<p style="text-align:center">Last updated: 2023/12/06 </p>
