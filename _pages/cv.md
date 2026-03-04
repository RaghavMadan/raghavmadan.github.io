---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Raghav Madan**  
raghavmadan2010@gmail.com · [LinkedIn](https://www.linkedin.com/in/raghav-madan) · +1 (412) 636-2649  
Seattle, WA, USA

**Interests:** Spatial neuroscience modeling · Human cognition · Neurodegenerative science · Neurodevelopmental science · Health tech innovation · Neurotech

---

## Education

* **Ph.D.** Biomedical and Health Informatics, University of Washington, USA (2020 – 2026)  
  *Dissertation: NeuroPathPredict — A data-driven paradigm to map the distribution of Alzheimer's disease neuropathology.*

* **M.S.** Engineering and Technology Innovation Management, Carnegie Mellon University, USA (2019 – 2020)

* **B.E.** Mechanical Engineering, Manipal Institute of Technology, India (2010 – 2014)

---

## Technical Skills

* **Programming languages:** Python, R, MATLAB, Bash, SQL, Linux, Java
* **Machine learning libraries:** SciPy, Scikit-learn, TensorFlow, PyTorch, glmnet, PySpark
* **Tools & frameworks:** JupyterLab, Git, Bitbucket, VS Code, Docker, LaTeX
* **ML models & techniques:** Linear/Logistic Regression, Decision Trees, XGBoost, Random Forest, K-Means, Lasso/Ridge/Elastic net, PCA, LSTM, RNN, Universal Kriging

---

## Research Experience

**Research Associate, University of Washington** (2020 – present)  
*Dr. Paul Crane, Dr. John Gennari — ACT study*

* Developed **NeuroPathPredict (NPP)**, a spatial modeling framework predicting Alzheimer's pathology from integrated neuroimaging and histopathology data.
* Created **Integrated Brain Information System (I-BIS)**, a customized brain coordinate system aligning structural and functional brain maps, with custom covariate engineering.
* Applied and benchmarked advanced spatial modeling techniques, including universal Kriging, for prediction of regional pathology spread.
* Deployed computationally intensive models on cloud infrastructure (AWS & Azure) for scalable neuroimaging analysis and reduced runtime for spatial inference.
* Conducted statistical comparison of cognitive classification approaches for mild cognitive impairment (MCI) using real-world cohort data; performed psychometric norming and sensitivity analyses.

**Research Associate, Carnegie Mellon University** (2019 – 2020)  
*Dr. Timothy Verstynen — Cognitive Axon Lab*

* Preprocessed and analyzed fMRI datasets to investigate network-level mechanisms of cortico-basal-ganglia-thalamus loops in human decision-making.
* Applied standard neuroimaging workflows (fMRIPrep) and developed custom Python scripts for signal cleaning, motion correction, and ROI extraction.

**Research Assistant, University of California San Francisco** (2019)  
*Dr. Theodore Zanto — Neuroscape Lab*

* Conducted a neuro-stimulation study to assess working memory and multi-tasking improvement using EEG, MRI, and tACS.
* Conducted market and feasibility research on digital therapeutic interventions for mental health, contributing to early-stage translational efforts in neurotechnology.

---

## Professional Experience

**Manager, Research & Development, Michelin India Technology Center** (2016 – 2018)

* Led cross-functional team of 16 engineers delivering analytics-driven product improvements.
* Improved product quality from 85% → 90% via statistical process control.
* Reduced defect losses by ~$100K annually through automated audit workflows.
* Managed $350K annual R&D budget using data-centered optimization.

**Product Design Engineer R&D, Michelin India Technology Center | Michelin Thailand** (2014 – 2016)

* Led technical transfer of product portfolio across Asia and Europe.
* Filed two design patents supporting Michelin's innovation pipeline.
* Standardized data workflows, reducing design cycle time by ~80%.

---

## Publications

<ul>
{% for post in site.publications reversed %}
  <li>
    <a href="{{ base_path }}{{ post.url }}">{{ post.title }}</a>.
    {% if post.venue %}<em>{{ post.venue }}</em>{% endif %}
    {% if post.date %}{{ post.date | date: "%Y" }}.{% endif %}
    {% if post.paperurl %} <a href="{{ post.paperurl }}">[Link]</a>{% endif %}
  </li>
{% endfor %}
</ul>

* Madan R. (2026). *NeuroPathPredict: A data-driven paradigm for spatial modeling of Alzheimer's Disease neuropathology.* Ph.D. Dissertation, University of Washington.
* Madan R. et al. (2026). *QNPtoVox: A methods pipeline for mapping 2D quantitative neuropathology to 3D MNI voxel space.* (Under review)

---

## Conferences and Talks

* Research talk — SEA-AD/Allen Institute AD Analysis Working Group meeting (November 2025).
* Poster — Center for Neural Circuit Mapping conference (August 2025).
* Research talk — Research in Progress Seminar (RIPS), University of Washington (October 2024).
* Poster — UW Alzheimer's Disease Research Center (ADRC) REC symposium (September 2022).

---

## References

References can be made available on request.
