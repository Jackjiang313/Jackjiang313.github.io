---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

The \* sign stands for co-first authors (equal contribution).

[PhantomLiDAR: Cross-modality Signal Injection  Attacks against LiDAR]()<br/>
Zizhi Jin, <strong>Qinhong Jiang<strong>, Xuancun Lu, Chen Yan, Xiaoyu Ji, Wenyuan Xu<br/>
In <em><strong>NDSS’25</strong>: The Network and Distributed System Security Symposium, 2025</em> <br/>

[Understanding Impacts of Electromagnetic Signal Injection Attacks on Object Detection](https://www.arxiv.org/pdf/2407.16327)<br/>
Youqian Zhang, Chunxi Yang, Eugene Y Fu, <strong>Qinhong Jiang<strong>, Chen Yan, Sze-Yiu Chau, Grace Ngai, Hong-Va Leong, Xiapu Luo, Wenyuan Xu)<br/>
In <em><strong>ICME'24</strong>: IEEE Conference on Multimedia Expo, 2024</em> ([Demo](https://sites.google.com/view/phantomlidar)) <br/>

[EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras](https://www.ndss-symposium.org/ndss-paper/em-eye-characterizing-electromagnetic-side-channel-eavesdropping-on-embedded-cameras/)<br/>
Yan Long\*, <strong>Qinhong Jiang\*</strong>, Chen Yan, Tobias Alam, Xiaoyu Ji, Wenyuan Xu, Kevin Fu.<br/>
In <em><strong>NDSS’24</strong>: The Network and Distributed System Security Symposium, 2024</em> ([PDF](https://www.ndss-symposium.org/wp-content/uploads/2024-552-paper.pdf), [Demo](https://emeyeattack.github.io/Website/)) <br/>


[GhostType: The Limits of Using Contactless Electromagnetic Interference to Inject Phantom Keys into Analog Circuits of Keyboards](https://www.ndss-symposium.org/ndss-paper/ghosttype-the-limits-of-using-contactless-electromagnetic-interference-to-inject-phantom-keys-into-analog-circuits-of-keyboards/)<br/>
<strong>Qinhong Jiang</strong>, Yanze Ren, Yan Long, Chen Yan, Yumai Sun, Xiaoyu Ji, Kevin Fu, Wenyuan Xu.<br/>
In <em><strong>NDSS’24</strong>: The Network and Distributed System Security Symposium, 2024</em> ([PDF](https://www.ndss-symposium.org/wp-content/uploads/2024-15-paper.pdf), [Demo](https://sites.google.com/view/ghosttype-demo))<br/>


[Watch Your Speed: Injecting Malicious Voice Commands via Time-Scale Modification](https://ieeexplore.ieee.org/abstract/document/10387471)<br/>
Xiaoyu Ji\*, <strong>Qinhong Jiang\*</strong>, Chaohao Li, Zhuoyang Shi, Wenyuan Xu.<br/>
In <em><strong>TIFS</strong>:  IEEE Transactions on Information Forensics and Security, 2024</em>([PDF](hhttps://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10387471), [Demo](https://sites.google.com/view/tsmae)) <br/>

[GlitchHiker: Uncovering Vulnerabilities of Image Signal Transmission with IEMI](https://www.usenix.org/conference/usenixsecurity23/presentation/jiang-qinhong)<br/>
<strong>Qinhong Jiang</strong>, Xiaoyu Ji, Chen Yan, Zhixin Xie, Haina Lou, and Wenyuan Xu.<br/>
In <em><strong>SEC'23</strong>: USENIX Security Symposium, 2023</em> ([PDF](https://www.usenix.org/system/files/usenixsecurity23-jiang-qinhong.pdf), [Presentation](https://www.youtube.com/watch?v=GIL4h_7k-qg&t=2s&ab_channel=USENIX))<br/>

[A Survey on Voice Assistant Security: Attacks and Countermeasures](https://dl.acm.org/doi/full/10.1145/3527153)<br/>
Chen Yan, Xiaoyu Ji, Kai Wang, <strong>Qinhong Jiang</strong>, Zizhi Jin, Wenyuan Xu.<br/>
In <em><strong>CSUR</strong>: ACM Computing Surveys, 55:4, 1-36, 2022 </em>([PDF](https://dl.acm.org/doi/full/10.1145/3527153))