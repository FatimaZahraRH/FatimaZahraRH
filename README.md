## Bonjour, je suis Fatima-Zahra

Élève ingénieure en cybersécurité à **Télécom SudParis**. Je travaille à la frontière entre **sécurité des systèmes** et **IA** : sécuriser les applications à base de LLM, et utiliser les LLM pour automatiser la défense.

Je recherche un **stage de fin d'études en cybersécurité** (2027).

Chaque projet ci-dessous est testé, mesuré, et documente honnêtement ses limites.


### Sécurité de l'IA et des agents

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**rag-redteam-framework**](https://github.com/FatimaZahraRH/RAG-redteam-framework-) | Attaque puis défend un système RAG : injections de prompt directes, indirectes, obfusquées et multi-tours, détecteur hybride règles + ML | Taux de succès des attaques **93,8 % → 6,2 %** |
| [**ci-agent-security-harness**](https://github.com/FatimaZahraRH/ci-agent-security-harness) | Teste un agent IA branché sur un pipeline CI/CD face à 6 injections indirectes cachées dans des issues, commentaires et logs | Taux de succès des attaques **100 % → 0 %** en 3 niveaux de garde-fous |

### Sécurité système et vérification formelle

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**cve-to-policy**](https://github.com/FatimaZahraRH/cve-to-policy) | À partir d'une CVE, observe le conteneur par eBPF et fait générer par un LLM une politique Tetragon qui bloque l'exploit, avec boucle de validation | Boucle génération → validation → correction fonctionnelle avec un vrai LLM |
| [**rocq-proof-agent**](https://github.com/FatimaZahraRH/rocq-proof-agent) | Un LLM propose des preuves formelles de propriétés de sécurité mémoire, Rocq les vérifie et renvoie l'erreur au LLM | Isolation mémoire : **0/11 → 7/11** théorèmes prouvés |

### Détection et sécurité des données

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**soc-alert-triage**](https://github.com/FatimaZahraRH/soc-alert-triage) | Détection d'intrusion réseau par ML + triage contextuel qui apprend des retours analystes | **−81,7 %** de faux positifs, **0 %** de faux négatifs |
| [**mini-dspm**](https://github.com/FatimaZahraRH/mini-dspm) | Scanner de données sensibles (RGPD, bancaires, secrets) avec checksums, entropie, NER et seuil calibré par courbe ROC | Précision **80 % → 100 %**, AUC 0,99 |
| [**aml-compliance-kpi**](https://github.com/FatimaZahraRH/aml-compliance-kpi) | Détection de blanchiment par features de graphe + KPI de conformité et reporting automatisés | AUC **0,992** sur split temporel |

### Gouvernance et conformité

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**governance-rag-copilot**](https://github.com/FatimaZahraRH/governance-rag-copilot) | Chatbot de gouvernance (ISO 27001, NIS2, RGPD) aux réponses toujours sourcées + scoring de conformité des fournisseurs | Recall@4 **0,875** · Precision@4 **0,938** |
| [**sbom-vuln-triage**](https://github.com/FatimaZahraRH/sbom-vuln-triage) | SBOM CycloneDX + priorisation des vulnérabilités par CVSS, EPSS et CISA KEV pour le Cyber Resilience Act | Faille réellement exploitée remontée **2ᵉ → 1ʳᵉ** priorité |

---

### Compétences

- **Sécurité de l'IA** : injection de prompt, red-teaming de LLM, sécurité des agents, OWASP LLM Top 10
- **Sécurité des systèmes et du cloud natif** : eBPF, Tetragon, sécurité des conteneurs, détection d'intrusion
- **Vérification formelle** : Rocq (Coq)
- **GRC et conformité** : ISO 27001, NIS2, RGPD, Cyber Resilience Act, SBOM, AML
- **IA et données** : RAG, ChromaDB, scikit-learn, NER (spaCy), évaluation ROC / indice de Youden
- **Développement** : Python, FastAPI, Plotly, pytest, Linux

**Contact** : [LinkedIn](https://www.linkedin.com/in/fatima-zahra-rhoulam-25fzrh2004/)
