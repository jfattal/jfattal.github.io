---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  * <b>Fattal J</b>, Martinez M,  Gupta T, Stevens J, Haase C, & Mittal VA (in review). Disrupted coherence between autonomic activation and emotional expression in individuals at clinical high risk for psychosis.
  * <b>Fattal J</b>, Giljen M, Vargas T, Calkins M, Pinkham AE, & Mittal VA (in review). A developmental perspective on early and current motor abnormalities and psychotic-like symptoms.
  * Lehet M, Rolfs M, Bao J, <b>Fattal J</b>, & Thakkar KN (in review). Pre-saccadic shifts of attention in individuals diagnosed with schizophrenia. 
  * Yao B, Rolfs M, Slate R, Roberts D, <b>Fattal J</b>, Achtyes ED, Tso I, Diwadkar V, Kashy D, Bao J, & Thakkar KN (2024). Abnormal oculomotor corollary discharge signaling as a trans-diagnostic mechanism of psychosis, <em>Schizophrenia Bulletin</em>.
  * Thakkar KN, Silverstein SM, <b>Fattal J</b>, Bao J, Slate R, Roberts D, & Brascamp JW (2024). Stronger tilt aftereffects in individuals diagnosed with schizophrenia spectrum disorders but not bipolar disorder, <em>Schizophrenia Research 264</em>, 345-353. doi: 10.1016/j.schres.2023.12.029.
  * <b>Fattal J</b>, Silverstein S, & Mittal VA (2023). Closed eye hallucinations in psychotic disorders, <em>Schizophrenia Research 260</em>, 65-66. doi: 10.1016/j.schres.2023.08.010 
  * <b>Fattal J</b>, Brascamp J, Slate RE, Achtyes ED, Lehet M, & Thakkar KN (2022). Blunted pupil light reflex is associated with negative symptoms and working memory in individuals with schizophrenia,  <em>Schizophrenia Research 248</em>, 254-262. doi: 10.1016/j.schres.2022.09.019
  * <b>Fattal J</b>, Brascamp J, Slate RE, Lehet M,Achtyes ED, & Thakkar KN (2020). [Abstract] Abnormal pupil light reflex relates to negative symptom severity in schizophrenia, <em>Biological Psychiatry 87</em>(9), Supplement, S138. doi: 10.1016/j.biopsych.2020.02.368

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
