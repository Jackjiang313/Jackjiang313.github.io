---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm Qinhong Jiang, a PhD candidate and security researcher at Zhejiang University. I work at the [Ubiquitous System Security Laboratory (USSLAB)](http://www.usslab.org/), where I'm honored to be advised by [Prof. Wenyuan Xu](https://scholar.google.com/citations?user=FCsdj0YAAAAJ&hl=en&oi=ao), [Prof. Xiaoyu Ji](https://scholar.google.com/citations?user=9D4UYBoAAAAJ&hl=en) and [Dr. Chen Yan](https://scholar.google.com/citations?user=qhaLpw8AAAAJ&hl=en&oi=sra).

My research aims to protect the security and privacy of electronic information systems, with an emphasis on their vulnerabilities against electromagnetic waves. 
Most of my research focuses on conducting intentional electromagnetic injection attacks to disrupt the reliability of electronic information systems and recovering private information from unintentional electromagnetic radiation from these systems.
The systems that I have analyzed and/or enhanced include sensors, voice assistants, cyber-physical systems, human-computer interaction devices, surveillance systems, and ubiquitous IoT devices. 
I work towards the next generation of IoT devices and systems that have AI-empowered and science-based security and privacy protections as a fundamental building block.
<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->

News
======
[Sep 15, 2023] My co-first authored EM Eye has been accepted at [NDSS’24](https://www.ndss-symposium.org/ndss2024/) without revisions. We demonstrate how attackers may visually spy on households by analyzing side-channel EM leakage of smart home cameras owned by the victim. Demos will be put up soon!
[June 22, 2023] My paper GhostType paper has been conditionally accepted at [NDSS’24](https://www.ndss-symposium.org/ndss2024/). We demonstrate how attackers may visually spy on households by analyzing side-channel EM leakage of smart home cameras owned by the victim. Demos will be put up soon!
[June 22, 2023] My paper GlitchHiker has been accepted at [USENIX’23](https://www.usenix.org/conference/usenixsecurity23). We demonstrate how attackers may visually spy on households by analyzing side-channel EM leakage of smart home cameras owned by the victim. Demos will be put up soon!

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.