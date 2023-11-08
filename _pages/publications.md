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

[EM Eye: Characterizing Electromagnetic Side-channel Eavesdropping on Embedded Cameras](https://www.usenix.org/conference/usenixsecurity23/presentation/jiang-qinhong)<br/>
Yan Long\*, <strong>Qinhong Jiang\*</strong>, Chen Yan, Tobias Alam, Xiaoyu Ji, Wenyuan Xu, Kevin Fu.<br/>
In <em><strong>NDSS’24</strong>: The Network and Distributed System Security Symposium, 2024</em> (To appear)<br/>