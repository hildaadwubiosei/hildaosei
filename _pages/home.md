---
title: "Home"
layout: homelay
sitemap: false
permalink: /
---

<h2 class="home-hero">{{ site.name }}</h2>
<p class="home-hero-sub">{{ site.title }}, {{ site.institution }}</p>

<div class="chip-container" markdown="0">
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Machine Learning</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Optimization and Decision Making</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">Fairness & Responsible AI</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">AI and Society</a>
<a href="{{ site.url }}{{ site.baseurl }}/research" class="chip">AI Safety & Robustness</a>
</div>


My research lies at the intersection of machine learning, optimization, fairness, and AI safety. I study a question that runs through both areas: when a decision-making system’s guarantee — that it is fair, or that it has learned the intended objective — is enforced only on an imperfect signal (a prediction, a reward signal, limited information), does that guarantee survive contact with the true outcome it was meant to protect? I study this through AI safety and alignment and through algorithmic fairness in resource allocation, grounded in real applications in agricultural markets, public health, and environmental systems in Ghana. My broader interest is in building decision-making systems that remain reliable, fair, and safe as they move from idealized guarantees to deployment in the real world.



<div class="callout callout-success" markdown="0">
<div class="callout-title"><i class="fa-solid fa-award callout-icon"></i>International "We, The Youth" Forum, 2025 </div>
<p>Selected as one of 150 delegates (from roughly 27,000 applicants) for the Global Youth Summit final in South Korea, after first being selected as one of 50 delegates from roughly 7,000 applicants at the Regional Conference in Botswana.</p>
</div>

<div class="banner-frame" markdown="0">
<img src="{{ site.url }}{{ site.baseurl }}\images\poster_presentation_knowledge.jpg" alt="Poster Presentation" loading="lazy">
<div class="banner-caption">Knowledge and Compliance with Standard Precautions for Nosocomial Infection Prevention among Undergraduate Nursing and Midwifery Students at a Ghanaian University., <em>medRxiv</em> (2026)</div>
</div>

### About me

I am a researcher and software developer from Ghana working at the intersection of machine learning, optimization, and AI safety. My path into research started with building software to solve practical problems, but I became increasingly interested in the decisions behind these systems: how predictions are used, what guarantees are made about them, and whether those guarantees actually hold once a system meets the real world.

That question now runs through my research. In one line of work, I study how a reinforcement learning agent can satisfy a reward signal completely while failing the true objective it was meant to represent, and derive a constrained learning method with a provable guarantee against this failure. In another, I study the same kind of gap in a different setting: whether a fairness constraint enforced on a model’s prediction still holds once the true outcome is observed, deriving a theoretical bound and confirming the effect on real US Census income data.

I ground this work in real, often imperfect data. Through FarmDirect, I study pricing, risk, and the economics of cutting out middlemen in Ghanaian agricultural markets, combining predictive modeling, risk-adjusted optimization, and agent-based simulation on real government price data. I have also worked on machine learning for health-risk prediction and computer-vision-based waste sorting in Ghana, and on infection-prevention research with colleagues in nursing and public health.

Across these projects, my aim is the same: to build decision-making systems whose guarantees aren’t just technically correct, but actually trustworthy once they leave the page and meet real outcomes, real people, and real constraints.

