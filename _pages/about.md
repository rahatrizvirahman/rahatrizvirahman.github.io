---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student in Computer Science at [Virginia Commonwealth University](https://www.vcu.edu/), advised by Prof. Kostadin Damevski. My work sits at the intersection of empirical software engineering and natural language processing. Before my Ph.D., I worked as a software engineer and as a research assistant in Dhaka, Bangladesh.

Research interests
======
I work in empirical software engineering, using natural language processing to study how developers communicate and how they work with AI. My current focus is **multi-turn human-AI conversations**. I study how these conversations unfold, where they go wrong, and how misalignment builds up between the person and the model. The aim is to reduce errors by predicting when a conversation is heading toward a failure, or when an AI-generated solution will need more work.

The same approach carries into my work on toxicity and conversational derailment in open-source communities, and on emotion recognition in virtual reality using facial movement and audio features.

Selected publications
======
{% include base_path %}
{% include paper-card-style.html %}
{% assign featured = site.publications | where: "featured", true | sort: "date" | reverse %}
{% for post in featured %}
{% include paper-card.html paper=post %}
{% endfor %}

[All publications]({{ base_path }}/publications/)

News
======
- **[2026]** Our paper on toxicity on GitHub at scale was published at [ASE 2026](https://doi.org/10.1145/3832783.3837505).
- **[2026]** *Toxicity Ahead: Forecasting Conversational Derailment on GitHub* was published at ICSE 2026. I attended the conference in Brazil and presented the paper.
- **[2026]** Our work on emotion recognition in VR was published in [Sensors](https://doi.org/10.3390/s26030845), and our pair programming study in [IJSEKE](https://doi.org/10.1142/S0218194026500294).
- **[Spring 2026]** Teaching Assistant for CMSC 425/525, Intro Software Analysis and Test, at VCU.
- **[November 2025]** Attended [VRST 2025](https://doi.org/10.1145/3756884.3766013) in Canada for our paper on detecting natural emotions in VR.
- **[August 2024]** Started my Ph.D. in Computer Science at VCU.

Education
======
- Ph.D. in Computer Science <br>
  **Virginia Commonwealth University** [August 2024 - Present] <br>
  Richmond, VA, USA
- B.Sc. in Computer Science and Engineering <br>
  **University of Dhaka** [January 2017 - August 2021] <br>
  Dhaka, Bangladesh <br>
  CGPA: 3.51 (on a scale of 4.0)

Research Experience
======
- Research Assistant [Fall 2024 - Present] <br>
  Department of Computer Science, Virginia Commonwealth University <br>
  Advisor: Prof. Kostadin Damevski
- Research Assistant [September 2023 - 2024] <br>
  [Center for Computational & Data Sciences (CCDS)](https://ccds.ai/), Independent University Bangladesh <br>
  Bangla language models
- Research Assistant [February 2022 - October 2022] <br>
  [AGenCy Lab](https://agencylab.github.io/), Independent University Bangladesh <br>
  Graph representation learning

Professional Experience
======
- Senior Software Engineer [November 2023 - July 2024], Software Engineer [November 2021 - October 2023] <br>
  [Enosis Solutions](https://www.enosisbd.com/) <br>
  Dhaka, Bangladesh
