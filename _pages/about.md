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

[//]: # (# 🥷🏃 About Me 📖 📝 📧 🖖)

I am currently pursuing my Ph.D. in Cryptography at [Wuhan University (WHU)](https://whu.edu.cn/), supervised by [Huanguo Zhang](https://jiamiwen.github.io/documents/Zhang.pdf). 
<br> I am also a CSC Visiting Ph.D. student at the [University of Wollongong (UOW)](http://uow.edu.au/), hosted by [Willy ](https://scholars.uow.edu.au/willy-susilo)[Susilo](https://sites.google.com/view/willy-susilo) and studying with the [iC$^2$](https://www.uow.edu.au/engineering-information-sciences/research/institute-cybersecurity-cryptology/). 

Before (Sep 2016 - Jun 2020), I completed my B.Sc. in Mathematics, also at Wuhan University.

My research interests are about cryptography and cyber security, to be more specific:
- Recently, my passion mainly lies in zero-knowledge proofs and privacy-preserving cryptographic primitives derived from them, mainly based on linear algebra assumptions that conjectured quantum-resistant (e.g., Lattice, Code, and Rank).
- In the long term, I hope using technologies to establish trust among individuals at almost zero cost, which I consider to be the most subtle and elegant aspect of cryptography.

Feel free to reach me via [cryptowjm at 163.com](mailto:cryptowjm@163.com) (perferred) or [wenjm at whu.edu.cn](mailto:wenjm@whu.edu.cn), if questions or we share common tastes.

# 📜 Publications
Here are the publications that I am the main contributor (also, as First Author or Corresponding Author). Generally, they can be classified into Conjectured Post-quantum and Pre-quantum. For other works, please see the links on the left panel of this page.

[//]: # (# [Google Scholar](https://scholar.google.com/citations?user=IoWa4fYAAAAJ) and [DBLP](https://dblp.uni-trier.de/pid/324/5245-1.html).)

## Conjectured Post-quantum (e.g., Lattice, Code, and Rank) 
- [WSZGZ24][Designated-Verifier Ring Signatures: Strong Definitions, Generic Constructions and Efficient Instantiations](http://www.icisc.org/static/program)
  <br> **Jiaming Wen**, Willy Susilo, Yanhua Zhang, Fuchun Guo, and Huanguo Zhang
  <br> *ICISC 2024* [[Conference](http://www.icisc.org/), [CACR-C](https://www.cacrnet.org.cn/site/content/1290.html), [Full Version](https://jiamiwen.github.io/documents/WSZGZ24.pdf), [Slides](https://jiamiwen.github.io/documents/DVRS-slides.pdf)]

- [WSYYZ24][Revocable ring signatures with CCA-Anonymity from standard lattices](https://www.sciencedirect.com/science/article/pii/S092054892400062X?via%3Dihub)
  <br> **Jiaming Wen**, Willy Susilo, Rupeng Yang, Zuoxia Yu, and Huanguo Zhang
  <br> *Computer Standards & Interfaces (CSI) 2024* [[Journal](https://www.sciencedirect.com/journal/computer-standards-and-interfaces), JCR Q1, 中科院2区]

- [WWZ23][Post-quantum Sigma Protocols and Signatures from Low-Rank Matrix Completions](https://link.springer.com/chapter/10.1007/978-3-031-45513-1_11)
  <br> **Jiaming Wen**, Houzhen Wang, and Huanguo Zhang
  <br> *ProvSec 2023* [[Conference](https://provsec2023.github.io/ProvSec2023/#), [CACR-C](https://www.cacrnet.org.cn/site/content/1290.html), [Slides](https://jiamiwen.github.io/documents/lrmc-slides.pdf)]

- [WBYZWH23][LaRRS: Lattice-Based Revocable Ring Signature and its application for VANETs](https://ieeexplore.ieee.org/document/10219003)
  <br> **Jiaming Wen**, Lu Bai, Zhichao Yang, Huanguo Zhang, Houzhen Wang, and Debiao He
  <br> *IEEE Transactions on Vehicular Technology (T-VT) 2023* [[Journal](https://vtsociety.org/publication/ieee-transactions-vehicular-technology), JCR Q1, 中科院2区, [Code by Lu](https://github.com/jiamiwen/LaRRS)]
  
- [WWLZ22][Aitps: A Two-Party Signature Scheme from Asymmetry Module Lattice Problems](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202220533) (in Chinese)
  <br> **Jiaming Wen**, Houzhen Wang, Jinhui Liu, and Huanguo Zhang
  <br> *Journal of Computer Research and Development (计算机研究与发展) 2023* [[Journal](https://crad.ict.ac.cn/), [Chinese CCF-T1](https://www.ccf.org.cn/ccftjgjxskwml/)]

- [WDWWZ25][Olithium: A Lattice-Based Online/Offline Signature Scheme without Trapdoors]() (in Chinese)
  <br> Houzhen Wang, Xiaochao Duan, **Jiaming Wen**✉️, Yahui Wang, and Huanguo Zhang (Initiator & Corresponding Author)
  <br> *Chinese Journal of Computers (计算机学报) 2025* [[Journal](http://cjc.ict.ac.cn/), [Chinese CCF-T1](https://www.ccf.org.cn/ccftjgjxskwml/), [Code by Xiaochao](https://github.com/jiamiwen/Olithium)]
  
  
## Pre-quantum (e.g., Group, Pairing, and RSA)
All in this category were done when I was a newcomer to the crypto world, but were accepted and published a long time later.
- [W24][Analysis and Improvement of a Conditional Privacy-Preserving Authentication Scheme with Double-Insurance in VANETs](https://ieeexplore.ieee.org/document/10592652)
  <br> **Jiaming Wen**, Lu Bai, Houzhen Wang, Jinhui Liu, Yahui Wang, and Huanguo Zhang
  <br> *IEEE Transactions on Vehicular Technology (T-VT) 2024* [[Journal](https://vtsociety.org/publication/ieee-transactions-vehicular-technology), JCR Q1, 中科院2区]

- [WWLZ23][ACKE: Asymmetric Computing Key Exchange Protocol for IoT Environments](https://ieeexplore.ieee.org/document/10131978)
  <br> Houzhen Wang, **Jiaming Wen**✉️, Jinhui Liu, and Huanguo Zhang (First Author is my co-advisor & Corresponding Author)
  <br> *IEEE Internet of Things Journal (IoT-J) 2023* [[Journal](https://ieee-iotj.org/), JCR Q1, 中科院1区]

[//]: # (# 🎖 Selected Honors and Awards)

# 💻 Services
## Teaching
- Feb 2023 - Jun 2023: **Teaching Assistant**
  <br>Program Design and Experimentation (undergraduate course in Spring 2023), Wuhan University
- Sep 2021 - Jan 2022: **Teaching Assistant**
  <br>Cryptography (undergraduate course in Fall 2021), Wuhan University

## Serving as Individual Reviewers
- Journals: *IEEE Internet of Things Journal (IoT-J)*, *IEEE Transactions on Vehicular Technology (T-VT)*, *Computer Networks*, *Journal of Information Security and Applications (JISA)*, *IEEE Systems Journal*, et al.
- Conferences: *Inscrypt 2023*, et al.

# 🧰 Misc
## Serendipity
My name starts with "jiami" (Chinese for "encrypt"), and ends with "mingwen" (Chinese for "plaintext"). 
<br>I remove "ng" from it to obtain "miwen" (Chinese for "ciphertext") for several usernames of mine, e.g., [wechat](https://jiamiwen.github.io/images/wechat.jpg), twitter, and github, as I believe it is more suitable for spreading over the public channel :)
## Some useful links
- [My bilibili space](https://space.bilibili.com/59630141), including several talks and courses that I am or was interested in.
- [IACR ePrint Archive](https://eprint.iacr.org/), a mysterious website suggested visiting every day.
- [The Lattice Club](https://thelatticeclub.com/), including so many resources about Lattice-based Cryptography.
- [Post-Quantum Signatures Zoo](https://pqshield.github.io/nist-sigs-zoo/), including an overview of Post-Quantum Signatures.
- [Kai-Min Chung's Homepage](https://homepage.iis.sinica.edu.tw/~kmchung/), including high-quality cryptography courses in Chinese.
- [Journal of WoCrypt](https://documents.uow.edu.au/~fuchun/jow.html), a very serious fake journal, whose outcomes include ["安全归约导论"](https://documents.uow.edu.au/~fuchun/book.html), ["数字签名密史"](https://documents.uow.edu.au/~fuchun/cryptologic-history.html) and its [slides](https://documents.uow.edu.au/~fuchun/methodology.html). Here are my always-unfinished [notes for the former](https://jiamiwen.github.io/documents/notes.pdf) and [xmind for the latter](https://jiamiwen.github.io/documents/xmind.pdf), which I hope are salutes to Prof. [Fuchun](https://documents.uow.edu.au/~fuchun/). 


[//]: # (# 💬 Invited Talks)
[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/))


<p style="text-align:center">Last updated: 07 Feb 2025 </p>
