---
permalink: /
title: "Dr. Artem Shelmanov / NLP Research Scientist"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an AI researcher committed to conducting high-impact research in natural language processing and artificial intelligence that drives positive change in the world. 
<br><br>
At [Mohamed bin Zayed University of Artificial Intelligence: MBZUAI](https://mbzuai.ac.ae/) (ranked 10th in AI globally), I work in the research group of [Prof. Timothy Baldwin](https://www.linkedin.com/in/timothybaldwin/) on one of the critical challenges in AI -- **LLM reliability**.
As a team leader, I drive research into robust uncertainty quantification (UQ) methods, aiming to effectively **detect and mitigate LLM hallucinations**. 
Our research aims to increase the applicability of AI technologies in safety-critical areas, such as healthcare and finance, as well as increase the performance of **multi-step reasoning systems such as LLM agents**. 
<br><br>
My team has created the most comprehensive UQ library for LLMs: [LM-Polygraph](https://github.com/IINemo/lm-polygraph).
<br><br>
We have presented our tutorial ["Uncertainty Quantification for LLMs"](https://sites.google.com/view/acl2025-uncertainty-for-llms/) at ACL-2025 in Vienna and will have a 2nd edition at AAAI-2026!

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
