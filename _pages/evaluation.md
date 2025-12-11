---
title: Evaluation
permalink: evaluation
---

## Evaluation Infrastructure

The HIPE-2026 evaluation infrastructure is designed to ensure fair, transparent, and reproducible assessment across both accuracy- and efficiency-focused system submissions. Participants will submit predictions on two blind test sets using a standardized format. The first data set ("Test Set A") comprises texts from the historical news domain and is used for ranking the main accuracy profile, the second is a suprise test set for evaluating accuracy in an out-of-domain generalization profile ("Test Set B"). Official scoring scripts will compute core classification metrics, using macro-averaged Recall (aka balanced accuracy) as the main measure (more details in our [guidelines](https://zenodo.org/records/17800136)).

Efficiency-related factors — such as model size and space usage — will be collected via metadata forms submitted by participants. These indicators will be used to rank systems within the efficiency profile, where cost-effective, scalable approaches are encouraged (more details in our [guidelines](https://zenodo.org/records/17800136)).

All evaluation tools, baseline resources, and submission templates will be made publicly available in our [data github repository](https://github.com/hipe-eval/hipe-2026-data) to support reproducibility and broad participation. 

---

Please check back or follow updates via the [mailing
list](https://groups.google.com/g/hipe-2026).
