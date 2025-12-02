---
permalink: /
title: "Dr. Artem Shelmanov / NLP Research Scientist"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


I am an AI researcher committed to conducting high-impact research in natural language processing and artificial intelligence that drives positive change in the world. At Mohamed bin Zayed University of Artificial Intelligence: MBZUAI (ranked 10th in AI globally), I work in the research group of Prof. Timothy Baldwin on one of the critical challenges in AI -- **LLM reliability**.
As a team leader, I drive research into robust uncertainty quantification (UQ) methods, aiming to effectively mitigate LLM hallucinations. My team has created the most comprehensive UQ library for LLMs: [LM-Polygraph](https://github.com/IINemo/lm-polygraph).
Our research aims to increase the applicability of AI technologies in safety-critical areas, such as healthcare and finance, as well as increase the performance of multi-step reasoning systems such as LLM agents, where each step needs to be accurately evaluated. 

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
