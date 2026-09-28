# AI-assisted cyber threat detection pipeline

```text
Telemetry / data sources
        │
        ▼
Collection & normalization
        │
        ▼
Feature engineering / representation
        │
        ▼
AI / ML model
        │
        ├──────────────► anomaly / threat score
        │
        ▼
Classification / correlation
        │
        ▼
SOC / SIEM alert
        │
        ▼
Analyst validation
        │
        ▼
Response & containment
        │
        ▼
Feedback / model monitoring
```

## Interpretation

The pipeline is a conceptual architecture, not a claim that every SOC implements these exact stages. Its purpose is to distinguish data preparation, model inference, alert generation, human validation, response, and continuous monitoring. The human-validation step is intentionally retained because model output is probabilistic and may generate false positives or false negatives.

The architecture is consistent with the report's research scope on intrusion detection, malware/phishing detection, behavioural analysis, SOC/SIEM automation and AI risk management.
