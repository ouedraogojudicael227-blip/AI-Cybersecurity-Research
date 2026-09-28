# AI & Cybersecurity — conceptual taxonomy

```text
                         AI IN CYBERSECURITY
                                  │
             ┌────────────────────┴────────────────────┐
             │                                         │
       DEFENSIVE USE                             AI-SPECIFIC RISK
             │                                         │
   ┌─────────┼─────────┐                    ┌──────────┼──────────┐
   │         │         │                    │          │          │
 IDS/IPS   Malware   Phishing          Evasion    Poisoning    Privacy
   │       detection  detection            │          │          │
   │         │         │              inference   training    data/model
   └─────────┼─────────┘                    │          │          │
             │                              └──────────┼──────────┘
     Behavioural analysis                              │
     Threat intelligence                        Mitigation & resilience
     SOC/SIEM automation
```

## Scientific basis

This diagram is a conceptual synthesis for the report. The defensive application categories are drawn from the reviewed cybersecurity/ML literature. The AI-specific risk categories follow NIST's 2025 adversarial machine learning taxonomy, which distinguishes attacks by AI system type, lifecycle stage, attacker objectives, capabilities and knowledge. NIST identifies evasion, poisoning and privacy attacks for predictive AI and also misuse attacks for generative AI.

Sources: NIST AI 100-2e2025; ENISA Artificial Intelligence and Cybersecurity Research (2023).
