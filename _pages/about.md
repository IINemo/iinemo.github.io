---
permalink: /
title: "Dr. Artem Shelmanov / Assistant Professor of Practice"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an AI researcher committed to conducting high-impact research in natural language processing and artificial intelligence that drives positive change in the world. 
<br><br>
At Mohamed bin Zayed University of Artificial Intelligence: MBZUAI (ranked 10th in AI globally), I work in the research group of [Prof. Timothy Baldwin](https://www.linkedin.com/in/timothybaldwin/) on one of the critical challenges in AI -- **LLM reliability**.
As a team leader, I drive research into robust uncertainty quantification (UQ) methods, aiming to effectively **detect and mitigate LLM hallucinations**. 
Our research aims to increase the applicability of AI technologies in safety-critical areas, such as healthcare and finance, as well as increase the performance of **multi-step reasoning systems such as LLM agents**. 
<br><br>
My team has created the most comprehensive UQ library for LLMs: [LM-Polygraph](https://github.com/IINemo/lm-polygraph).
<br><br>
We have presented our tutorial ["Uncertainty Quantification for LLMs"](https://sites.google.com/view/acl2025-uncertainty-for-llms/) at ACL-2025 in Vienna, AAAI-2026, and ECIR-2026. Our new tutorial, **"Uncertainty Quantification: From Detecting LLM Hallucinations to Strengthening Reasoning and AI Agents,"** has been [accepted at NeurIPS-2026 in Sydney](https://www.linkedin.com/feed/update/urn:li:activity:7495134756410544128/). It focuses on uncertainty as a control signal for reliable reasoning, adaptive test-time compute, and safer tool use.

## Recent News

- **29 October 2026 (upcoming):** I am co-organizing [**UncertaiNLP 2026: Third Workshop on Uncertainty-Aware NLP**](https://uncertainlp.github.io/) at **EMNLP-2026 in Budapest, Hungary**. The workshop received the **highest number of submissions among all EMNLP 2026 workshops**.
- **August 2026:** I presented **"Uncertainty Quantification for LLMs: From Hallucination Detection to Stronger Reasoning and Agentic AI"** at Aalborg University, Denmark.
- **July 2026:** Our paper **"ReProbe: Efficient Test-Time Scaling of Multi-Step Reasoning by Probing Internal States of Large Language Models"** was presented as an [**oral presentation at ACL-2026 in San Diego**](https://www.linkedin.com/posts/artem-shelmanov-995553a8_acl2026-reprobe-thinkbooster-activity-7480108387452469248-gpWx).
- **June 2026:** My PhD student **Gleb Kuzmin**, co-supervised with Prof. Ivan Smirnov, [successfully defended his thesis at HSE University](https://www.linkedin.com/feed/update/urn:li:activity:7486440233882767362/). Congratulations, Dr. Kuzmin!
- **2026:** I received the [**Gold Reviewer** award at **ICML-2026**](https://www.linkedin.com/posts/artem-shelmanov-995553a8_icml2026-activity-7460430207225700352-bIAP), recognizing the quality of my reviews.
- **2026:** I received the [**Outstanding Teaching Assistant and Peer Mentor - Researcher Award** at **MBZUAI**](https://www.linkedin.com/posts/artem-shelmanov-995553a8_mbzuai-nlp-activity-7427320306631061504-EnJ0), presented as part of the university’s fifth anniversary celebration.

## Graduated Students

{% if site.data.students and site.data.students.size > 0 %}
<ul>
{% for s in site.data.students %}
  <li>
    {% if s.link %}<a href="{{ s.link }}">{% endif %}{{ s.name }}{% if s.link %}</a>{% endif %}{% if s.note %} — {{ s.note }}{% endif %}
  </li>
{% endfor %}
</ul>
{% else %}
<p>Coming soon.</p>
{% endif %}
