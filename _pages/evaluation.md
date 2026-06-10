---
title: Evaluation
permalink: evaluation
---

**News 2026/05/19**: Official HIPE-2026 results are now available on the [Results](/HIPE-2026/results) page, including generated reports, ranking tables, diagnostics, and downloadable result archives.

**News 2026/05/05**: The test phase started, and the [official test set](https://github.com/hipe-eval/HIPE-2026-data/tree/main/official_test_unlabeled) was released. The submission deadline was 2026/05/07 AoE.

## On This Page

- [Evaluation Overview](#evaluation-overview)
- [Evaluation Profiles](#evaluation-profiles)
- [Metrics](#metrics)
- [Efficiency Metadata](#efficiency-metadata)
- [Resources](#resources)
- [Baseline](#minimal-baseline)

## Evaluation Overview

The HIPE-2026 evaluation infrastructure supports fair, transparent, and reproducible assessment of person-place relation extraction systems. Participants submitted predictions for blind test data in a standardized JSONL format, and the official scorer produced per-run scores, rankings, diagnostics, and downloadable result archives.

The official results are available on the [Results](/HIPE-2026/results) page. The evaluation code, submitted systems, generated reports, and diagnostics are available in the [evaluation repository](https://github.com/hipe-eval/hipe-2026-eval).

## Evaluation Profiles

HIPE-2026 reports three main evaluation profiles:

- **Accuracy Profile**: performance on the multilingual `impresso` newspaper test data.
- **Generalization Profile**: performance on the out-of-domain `surprise` test data.
- **Accuracy-Efficiency Profile**: a combined view of system performance and model footprint.

The original participation guidelines describe these as Test A and Test B. On the website and in the generated reports, we use the dataset names `impresso` and `surprise` to make the profile tables easier to interpret.

## Metrics

The primary official ranking criterion is macro-averaged Recall, also known as balanced accuracy. This gives each label equal weight and is therefore more informative than plain accuracy when labels are imbalanced.

The generated reports also include accuracy and additional macro-averaged metrics where relevant. More details are available in the [participation guidelines](https://zenodo.org/records/17800136).

## Efficiency Metadata

Participants submitted metadata about model size and parameter count for each run. These values are used for the efficiency-oriented profiles, where cost-effective and scalable approaches are encouraged alongside strong prediction quality.

## Resources

The main public resources are:

- [Task data and scorer](https://github.com/hipe-eval/HIPE-2026-data)
- [Evaluation repository, submissions, and results](https://github.com/hipe-eval/hipe-2026-eval)
- [Official results page](/HIPE-2026/results)

## Minimal Baseline

We provide a minimal baseline implementation to help participants get started. The baseline code is available at [hipe-eval/hipe-2026-llm-baseline](https://github.com/hipe-eval/hipe-2026-llm-baseline), with setup instructions in the [baseline README](https://github.com/hipe-eval/hipe-2026-llm-baseline/blob/main/README.md).

The baseline run is included in the official rankings and generated reports on the [Results](/HIPE-2026/results) page.

Please follow updates via the [mailing list](https://groups.google.com/g/hipe-2026).
