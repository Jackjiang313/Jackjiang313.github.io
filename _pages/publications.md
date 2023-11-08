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

[EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras]()<br/>
Yan Long\*, <strong>Qinhong Jiang\*</strong>, Chen Yan, Tobias Alam, Xiaoyu Ji, Wenyuan Xu, Kevin Fu.<br/>
In <em><strong>NDSS’24</strong>: The Network and Distributed System Security Symposium, 2024</em> (To appear)<br/>


[GhostType: The Limits of Using Contactless Electromagnetic Interference to Inject Phantom Keys into Analog Circuits of Keyboards]()<br/>
<strong>Qinhong Jiang</strong>, Yanze Ren, Yan Long, Chen Yan, Yumai Sun, Xiaoyu Ji, Kevin Fu, Wenyuan Xu.<br/>
In <em><strong>NDSS’24</strong>: The Network and Distributed System Security Symposium, 2024</em> (To appear)<br/>


[GlitchHiker: Uncovering Vulnerabilities of Image Signal Transmission with IEMI](https://www.usenix.org/conference/usenixsecurity23/presentation/jiang-qinhong)<br/>
<strong>Qinhong Jiang</strong>, Xiaoyu Ji, Chen Yan, Zhixin Xie, Haina Lou, and Wenyuan Xu.<br/>
In <em><strong>SEC'23</strong>: USENIX Security Symposium, 2023</em> ([PDF](https://www.usenix.org/system/files/usenixsecurity23-jiang-qinhong.pdf))<br/>


[A Survey on Voice Assistant Security: Attacks and Countermeasures](https://dl.acm.org/doi/full/10.1145/3527153)<br/>
Chen Yan, Xiaoyu Ji, Kai Wang, <strong>Qinhong Jiang</strong>, Zizhi Jin, Wenyuan Xu.<br/>
In <em><strong>CSUR</strong>: ACM Computing Surveys, 55:4, 1-36, 2022 </em>([PDF](https://dl.acm.org/doi/full/10.1145/3527153))