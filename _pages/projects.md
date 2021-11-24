---
title: "Archive Layout with Content"
layout: projects
permalink: /projects/
---

## KGRefiner

KGRefiner is a novel refining method for refining knowledge graphs. This method helps link prediction algorithms outperform by using hierarchical information in knowledge graphs. Paper: [KGRefiner: Knowledge Graph Refinement for Improving Accuracy of Translational Link Prediction Methods](https://arxiv.org/pdf/2106.14233.pdf).



{% include base_path %}
{% for post in site.pages %}
{% include archive-single.html %}
{% endfor %}
