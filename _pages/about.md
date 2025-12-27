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

In Dec 2025, I concluded my Ph.D. in Cyber Security at [Wuhan University (WHU)](https://whu.edu.cn/). My supervisor is [Huanguo Zhang](https://jiamiwen.github.io/documents/Zhang.pdf).

Before (Jun 2025 - Aug 2025), I worked as an algorithm engineer intern at [Ant Group](https://www.antgroup.com/), affiliated with [Misuan](https://www.misuan.com/).
<br>
Before (Dec 2023 - Mar 2025), I was a CSC Visiting Ph.D. student at the [University of Wollongong (UOW)](http://uow.edu.au/), Australia. There, I was hosted by [Willy Susilo](https://scholars.uow.edu.au/willy-susilo) and had the fortune to study with the [Institute of Cybersecurity and Cryptology (iC$^2$)](https://www.uow.edu.au/engineering-information-sciences/research/institute-cybersecurity-cryptology/) led by him.
<br>
Before (Sep 2016 - Jun 2020), I earned my B.S. in Mathematics from Wuhan University, where I continued with my Ph.D. studies.

My research focuses on cryptography and cyber security, to be more specific:
- Recently, my passion lies in lattice-based cryptogtaphy, particularly zero-knowledge proofs and their applications.
- In the long term, I hope using technologies to establish trust among individuals, which I consider to be the most subtle and elegant aspect of cryptography.

I can be reached via [wenjm at whu.edu.cn](mailto:wenjm@whu.edu.cn) or [cryptowjm at 163.com](mailto:cryptowjm@163.com), if questions or we share common tastes.

# 📜 Publications
Here are the publications that I am the main contributor (also, as First Author or Corresponding Author). For other works, please see the links on the left panel of this page.

[//]: # (# [Google Scholar](https://scholar.google.com/citations?user=IoWa4fYAAAAJ) and [DBLP](https://dblp.uni-trier.de/pid/324/5245-1.html).)

## Signature, Zero-Knowledge, and Authentication
- [WSZGZ24][Designated-Verifier Ring Signatures: Strong Definitions, Generic Constructions and Efficient Instantiations](https://link.springer.com/chapter/10.1007/978-981-96-5566-3_3)
  <br> **Jiaming Wen**, Willy Susilo, Yanhua Zhang, Fuchun Guo, and Huanguo Zhang
  <br> *ICISC 2024* [[Conference](http://www.icisc.org/), [CACR-C](https://www.cacrnet.org.cn/site/content/1290.html), [Full Version](https://jiamiwen.github.io/documents/WSZGZ24.pdf), [Slides](https://jiamiwen.github.io/documents/DVRS-slides.pdf)]

- [WSYYZ24][Revocable ring signatures with CCA-Anonymity from standard lattices](https://www.sciencedirect.com/science/article/pii/S092054892400062X?via%3Dihub) (follow-up work of [WBYZWH24])
  <br> **Jiaming Wen**, Willy Susilo, Rupeng Yang, Zuoxia Yu, and Huanguo Zhang
  <br> *Computer Standards & Interfaces (CSI) 2024* [[Journal](https://www.sciencedirect.com/journal/computer-standards-and-interfaces), JCR Q1, 中科院2区]

- [WBYZWH24][LaRRS: Lattice-Based Revocable Ring Signature and its application for VANETs](https://ieeexplore.ieee.org/document/10219003)
  <br> **Jiaming Wen**, Lu Bai, Zhichao Yang, Huanguo Zhang, Houzhen Wang, and Debiao He
  <br> *IEEE Transactions on Vehicular Technology (T-VT) 2024* [[Journal](https://vtsociety.org/publication/ieee-transactions-vehicular-technology), JCR Q1, 中科院2区, [Code by Lu](https://github.com/jiamiwen/LaRRS)]

- [W24][Analysis and Improvement of a Conditional Privacy-Preserving Authentication Scheme with Double-Insurance in VANETs](https://ieeexplore.ieee.org/document/10592652)
  <br> **Jiaming Wen**, Lu Bai, Houzhen Wang, Jinhui Liu, Yahui Wang, and Huanguo Zhang
  <br> *IEEE Transactions on Vehicular Technology (T-VT) 2024* [[Journal](https://vtsociety.org/publication/ieee-transactions-vehicular-technology), JCR Q1, 中科院2区]

- [WWZ23][Post-quantum Sigma Protocols and Signatures from Low-Rank Matrix Completions](https://link.springer.com/chapter/10.1007/978-3-031-45513-1_11)
  <br> **Jiaming Wen**, Houzhen Wang, and Huanguo Zhang
  <br> *ProvSec 2023* [[Conference](https://provsec2023.github.io/ProvSec2023/#), [CACR-C](https://www.cacrnet.org.cn/site/content/1290.html), [Slides](https://jiamiwen.github.io/documents/lrmc-slides.pdf)]
  
- [WWLZ23_SIG][Aitps: A Two-Party Signature Scheme from Asymmetry Module Lattice Problems](https://crad.ict.ac.cn/cn/article/doi/10.7544/issn1000-1239.202220533) (in Chinese)
  <br> **Jiaming Wen**, Houzhen Wang, Jinhui Liu, and Huanguo Zhang
  <br> *Journal of Computer Research and Development (计算机研究与发展) 2023* [[Journal](https://crad.ict.ac.cn/), [Chinese CCF-T1](https://www.ccf.org.cn/ccftjgjxskwml/)]

- [WDWWZ25][Olithium: A Lattice-Based Online/Offline Signature Scheme without Trapdoors](http://cjc.ict.ac.cn/online/onlinepaper/whz-2025424155959.pdf) (in Chinese)
  <br> Houzhen Wang, Xiaochao Duan, **Jiaming Wen**✉️, Yahui Wang, and Huanguo Zhang (Supervision & Corresponding Author)
  <br> *Chinese Journal of Computers (计算机学报) 2025* [[Journal](http://cjc.ict.ac.cn/), [Chinese CCF-T1](https://www.ccf.org.cn/ccftjgjxskwml/), [Code by Xiaochao](https://github.com/jiamiwen/Olithium)]
  
  
## Key Exchange and Group Key Distribution
- [WWQW26][ChatKID: Identity-Based Group Key Distribution Protocol for Instant Messaging]() (follow-up work of [WWLZ23_KE])
  <br> Houzhen Wang, Jiayimei Wang, Wanying Qin, and **Jiaming Wen**✉️ (Supervision & Corresponding Author)
  <br> *IEEE Transactions on Dependable and Secure Computing (T-DSC) 2026* [[Journal](https://www.computer.org/csdl/journal/tq), JCR Q1, [CCF-A](https://www.ccf.org.cn/Academic_Evaluation/NIS/)]

- [WWLZ23_KE][ACKE: Asymmetric Computing Key Exchange Protocol for IoT Environments](https://ieeexplore.ieee.org/document/10131978)
  <br> Houzhen Wang, **Jiaming Wen**✉️, Jinhui Liu, and Huanguo Zhang (First Author is my co-advisor & Corresponding Author)
  <br> *IEEE Internet of Things Journal (IoT-J) 2023* [[Journal](https://ieee-iotj.org/), JCR Q1, 中科院1区]

[//]: # (# Most in this category were done when I was a newcomer to the crypto world, but were accepted and published until much later.)

[//]: # (# 🎖 Selected Honors and Awards)

# 💻 Services
## Teaching
- Feb 2023 - Jun 2023: **Teaching Assistant**
  <br>Program Design and Experimentation (undergraduate course in Spring 2023), Wuhan University
- Sep 2021 - Jan 2022: **Teaching Assistant**
  <br>Cryptography (undergraduate course in Fall 2021), Wuhan University

## Serving as Reviewers
- **Journals**: *IEEE Transactions on Information Theory (T-IT)*, *IEEE Transactions on Dependable and Secure Computing (T-DSC)*, *IEEE Transactions on Vehicular Technology (T-VT)*, *IEEE Internet of Things Journal (IoT-J)*, *Journal of Information Security and Applications (JISA)*, etc.
- **Conferences**: *ICISC 2024*, *Inscrypt 2023*, etc.

# 🧰 Misc
## Serendipity
My name starts with "jiami" (Chinese for "encrypt"), and ends with "mingwen" (Chinese for "plaintext"). 
<br>I remove "ng" from it to obtain "miwen" (Chinese for "ciphertext") for several usernames of mine, e.g., [wechat](https://jiamiwen.github.io/images/wechat.jpg), twitter, and github, as I believe it is more suitable for spreading over the public channel :)
## Some useful links
- [IACR ePrint Archive](https://eprint.iacr.org/), a mysterious website suggested visiting every day.
- [The Lattice Club](https://thelatticeclub.com/), including so many resources about Lattice-based Cryptography.
- [Post-Quantum Signatures Zoo](https://pqshield.github.io/nist-sigs-zoo/), including an overview of Post-Quantum Signatures.
- [Kai-Min Chung's Homepage](https://homepage.iis.sinica.edu.tw/~kmchung/), including high-quality theoretical cryptography courses in Chinese.
- [Fuchun Guo's Homepage](https://documents.uow.edu.au/~fuchun/), including valuable materials for cryptography studies (temporarily on an interstellar trip).


[//]: # (# 💬 Invited Talks)
[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/))


<p style="text-align:center">Last updated: 27 Dec 2025 </p>
