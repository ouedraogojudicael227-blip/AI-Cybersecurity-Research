# AI & Cybersecurity Research

> **A documentary research study on how artificial intelligence is transforming cybersecurity — and how cybersecurity must evolve to secure AI itself.**

**Author:** Judicaël Ouedraogo  
**Status:** Manuscript validated · PDF production pending

## Research question

> **How is artificial intelligence transforming the detection and prevention of cyber threats, and what limitations and new risks arise from its use in cybersecurity?**

## Abstract

This project investigates the use of artificial intelligence in cybersecurity, with a focus on intrusion detection, malware and phishing detection, behavioral analysis, SOC/SIEM support and threat intelligence. It also examines the limitations of AI-based security systems and the security risks introduced by the models themselves, including adversarial machine learning, data poisoning, explainability, data quality and privacy.

The project deliberately distinguishes **documented evidence, experimental results, interpretation and future perspectives**. Quantitative claims are not treated as universal performance indicators: each result is linked to its dataset, method and evaluation protocol.

## Objectives

### General objective
Analyze how AI changes cyber-threat detection and prevention while assessing its technical limitations, operational risks and future prospects.

### Specific objectives

- Identify major AI applications in defensive cybersecurity.
- Compare documented approaches and quantitative results.
- Examine the role of data quality, evaluation metrics and generalization.
- Analyze adversarial attacks, poisoning and other threats against AI systems.
- Study offensive uses of AI from a cybersecurity-risk perspective.
- Identify emerging research directions and deployment challenges.

## Research methodology

The study is based primarily on:

- peer-reviewed scientific and academic publications;
- government and standards organizations;
- CERT/CSIRT and international organizations;
- technical reports and official documentation;
- relevant cybersecurity-industry research.

### Evidence rules

1. **No invented statistics or sources.**
2. Every quantitative claim must have an identifiable source.
3. Experimental metrics are interpreted in the context of their dataset and protocol.
4. Accuracy is not considered sufficient on its own when class imbalance or other evaluation issues matter.
5. Facts, experimental findings, interpretations and hypotheses are explicitly distinguished.
6. Industry reports are used as contextual evidence, not automatically treated as peer-reviewed research.

## Research scope

- AI and cybersecurity foundations
- Intrusion detection
- Malware detection
- Phishing detection
- Behavioral analysis
- SOC / SIEM
- Threat intelligence
- Benefits and operational value
- False positives / false negatives
- Data quality, bias and explainability
- Adversarial machine learning
- Data poisoning and model attacks
- Privacy and model security
- Offensive uses of AI
- Real-world case studies
- Quantitative evidence and visualization
- Future perspectives

## Repository structure

```text
AI-Cybersecurity-Research/
├── README.md
├── report/
│   └── AI_Cybersecurity_Study.pdf
├── research/
│   ├── foundations.md
│   ├── applications.md
│   ├── benefits.md
│   ├── limitations.md
│   ├── offensive_ai.md
│   └── perspectives.md
├── data/
│   ├── sources.csv
│   ├── studies.csv
│   └── datasets/
├── analysis/
│   └── analysis.ipynb
├── figures/
│   ├── applications/
│   ├── technologies/
│   ├── evolution/
│   └── limitations/
├── diagrams/
│   ├── ai_cybersecurity_architecture.png
│   └── detection_pipeline.png
└── references/
    └── bibliography.bib
```

## Quantitative corpus

The current `data/studies.csv` records quantitative studies covering intrusion detection, Android malware, phishing, behavioral detection and unseen/zero-day attack detection. The dataset records the **method, dataset, task, metrics, results, limitations and source identifier** for each study.

> Results from different datasets and protocols must **not** be interpreted as a universal ranking of models.

## Planned visual analysis

The study will produce reproducible visuals where the available evidence supports them, including:

- comparison of reported model metrics;
- application-domain distribution;
- evolution of selected research indicators over time;
- limitations and risk taxonomy;
- AI-assisted cybersecurity architecture;
- AI detection and response pipeline.

No chart will be presented as a global statistic unless the underlying source supports that interpretation.

## Project status

- [x] Research framework
- [x] Research question and objectives
- [x] Source collection and validation phase
- [x] Quantitative study extraction
- [x] Manuscript validation
- [x] Initial repository architecture
- [x] README review
- [ ] Final LaTeX/PDF production
- [ ] Final figures and diagrams
- [ ] Final repository audit

## Quality standard

This repository is intended as a **research portfolio project**, not a generic school presentation. The priority is traceability: a reader should be able to move from a claim to the underlying study, dataset, metric and source.

## Author

**Judicaël Ouedraogo**
