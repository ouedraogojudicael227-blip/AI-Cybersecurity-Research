# Data Dictionary — Quantitative Evidence

## Purpose

This document defines the variables used in the quantitative evidence collected for the AI & Cybersecurity Research project.

## Core fields

| Field | Definition | Rule |
|---|---|---|
| `study_id` | Unique identifier for an extracted study/result | Stable identifier; never reused |
| `domain` | Cybersecurity application or research domain | IDS, malware, phishing, behavioral detection, zero-day/unseen, etc. |
| `source_id` | Identifier linking the result to the verified source register | Must correspond to `data/sources.csv` |
| `year` | Publication year | Use the publication year of the cited study |
| `dataset` | Dataset or benchmark used in the experiment | Preserve the study's naming |
| `model_or_technique` | ML/DL model or method evaluated | Preserve the reported method |
| `accuracy` | Fraction of correct predictions among all predictions | Report as percentage when the source reports it that way |
| `precision` | Fraction of predicted positives that are true positives | Do not infer if not reported |
| `recall` | Fraction of actual positives detected | Do not infer if not reported |
| `f1_score` | Harmonic mean of precision and recall | Do not infer if not reported |
| `evaluation_type` | Experimental setting | e.g. test set, unseen data, cross-validation |
| `limitations` | Important methodological limitations or scope conditions | Record rather than silently generalize |

## Interpretation rules

1. A missing metric is represented by `--`; it is **not zero**.
2. Results from different datasets, tasks, class distributions, and protocols are not automatically comparable.
3. Accuracy alone is insufficient when class imbalance may affect the evaluation.
4. `unseen` means data/classes not observed during the relevant training protocol. It must not automatically be treated as synonymous with every real-world zero-day attack.
5. A reported experimental performance must not be generalized to all deployments.
6. Every quantitative value must have an identifiable source.
7. We do not calculate or invent a metric that the cited study did not report unless the calculation is explicitly documented and reproducible from published values.

## Quality-control status

The master table is an evidence-extraction working dataset. Before inclusion in the final report, each quantitative result should be checked against the original paper/table and linked to its exact source location.
