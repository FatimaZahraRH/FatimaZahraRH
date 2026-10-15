## Bonjour, je suis Fatima-Zahra

Élève ingénieure en cybersécurité à **Télécom SudParis** (Institut Polytechnique de Paris), option Sécurité des systèmes et des réseaux.

Ce qui me motive, c'est la **sécurité opérationnelle** : traiter un incident, trier des alertes, prioriser les bons correctifs, et aider les équipes à adopter les bons réflexes. Je m'appuie aussi sur l'**IA**, à la fois pour automatiser la défense et pour sécuriser les applications à base de LLM.

Je recherche un **stage de fin d'études en cybersécurité** (6 mois, à partir de février 2027).

Chaque projet ci-dessous s'inspire de travaux de recherche récents, est testé et mesuré, et documente honnêtement ses limites.


### Sécurité opérationnelle (SecOps / SOC)

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**Phishing Report Triage**](https://github.com/FatimaZahraRH/Phishing_Report_Triage) | Traite la boîte où les employés signalent les e-mails suspects : analyse des en-têtes (SPF/DKIM/DMARC), verdict expliqué, regroupement en campagnes, tickets priorisés et réponse à chaque signaleur (FR/EN) | **362 signalements → 75 tickets**, 0 phishing clos à tort sur 2 998 vrais e-mails |
| [**Phishing Campaign Analyzer**](https://github.com/FatimaZahraRH/Phishing-Campaign-Analyzer) | Analyse des campagnes de sensibilisation au phishing : difficulté notée (NIST Phish Scale), effet de la formation contre groupe témoin, signalement, rapport FR/EN au RSSI | Révèle qu'une baisse des clics **22,8 % → 7,2 %** venait de leurres plus faciles ; méthode validée sur 200 simulations |
| [**Installed Apps Review**](https://github.com/FatimaZahraRH/Installed-Apps-Review) | Revue automatisée des applications d'un parc Windows : politique logicielle, fin de support, failles (NVD, CISA KEV, EPSS) et plan de correction | **97 %** des failles exploitées couvertes contre 86 % pour la méthode publiée, à charge égale |
| [**SOC Detection Lab**](https://github.com/FatimaZahraRH/soc-detection-lab) | Règles de détection Sigma sur de vrais journaux d'attaque Windows (MITRE ATT&CK), réglage des faux positifs et audit des exclusions | Fausses alertes **150 → 0** sans perdre une seule détection |
| [**soc-alert-triage**](https://github.com/FatimaZahraRH/soc-alert-triage) | Détection d'intrusion réseau par ML et triage contextuel qui apprend des retours des analystes | **−81,7 %** de faux positifs, **0 %** de faux négatifs |

### Sécurité de l'IA et des agents

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**rag-redteam-framework**](https://github.com/FatimaZahraRH/RAG-redteam-framework) | Attaque puis défend un système RAG : injections de prompt directes, indirectes, obfusquées et multi-tours, détecteur hybride règles + ML | Taux de succès des attaques **93,8 % → 6,2 %** |
| [**ci-agent-security-harness**](https://github.com/FatimaZahraRH/ci-agent-security-harness) | Teste un agent IA branché sur un pipeline CI/CD face à 6 injections indirectes cachées dans des issues, commentaires et logs | Taux de succès des attaques **100 % → 0 %** en 3 niveaux de garde-fous |

### Sécurité système et vérification formelle

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**cve-to-policy**](https://github.com/FatimaZahraRH/cve-to-policy) | À partir d'une CVE, observe le conteneur par eBPF et fait générer par un LLM une politique Tetragon qui bloque l'exploit, avec boucle de validation | Boucle génération → validation → correction fonctionnelle avec un vrai LLM |
| [**rocq-proof-agent**](https://github.com/FatimaZahraRH/rocq-proof-agent) | Un LLM propose des preuves formelles de propriétés de sécurité mémoire, Rocq les vérifie et renvoie l'erreur au LLM | Isolation mémoire : **0/11 → 7/11** théorèmes prouvés |

### Vulnérabilités, données et conformité

| Projet | Ce qu'il fait | Résultat clé |
|---|---|---|
| [**sbom-vuln-triage**](https://github.com/FatimaZahraRH/sbom-vuln-triage) | SBOM CycloneDX + priorisation des vulnérabilités par CVSS, EPSS et CISA KEV pour le Cyber Resilience Act | Faille réellement exploitée remontée **2ᵉ → 1ʳᵉ** priorité |
| [**mini-dspm**](https://github.com/FatimaZahraRH/mini-dspm) | Scanner de données sensibles (RGPD, bancaires, secrets) avec checksums, entropie, NER et seuil calibré par courbe ROC | Précision **80 % → 100 %**, AUC 0,99 |
| [**governance-rag-copilot**](https://github.com/FatimaZahraRH/governance-rag-copilot) | Chatbot de gouvernance (ISO 27001, NIS2, RGPD) aux réponses toujours sourcées + scoring de conformité des fournisseurs | Recall@4 **0,875** · Precision@4 **0,938** |
| [**aml-compliance-kpi**](https://github.com/FatimaZahraRH/aml-compliance-kpi) | Détection de blanchiment par features de graphe + KPI de conformité et reporting automatisés | AUC **0,992** sur split temporel |

---

### Compétences

- **Sécurité opérationnelle** : gestion d'incidents et de tickets, triage d'alertes, règles Sigma, MITRE ATT&CK, journaux Windows (Sysmon)
- **Phishing et sensibilisation** : analyse d'e-mails (SPF/DKIM/DMARC, IOC), campagnes d'entraînement, NIST Phish Scale
- **Gestion des vulnérabilités** : CVE, CVSS, EPSS, CISA KEV, appariement CPE, plans de correction
- **Sécurité de l'IA** : injection de prompt, red-teaming de LLM, sécurité des agents, OWASP LLM Top 10
- **Sécurité des systèmes et du cloud natif** : eBPF, Tetragon, conteneurs, détection d'intrusion, vérification formelle (Rocq)
- **GRC et conformité** : ISO 27001, NIS2, RGPD, Cyber Resilience Act
- **Données et développement** : Python, statistiques, scikit-learn, RAG, pytest, Linux

**Certifications en préparation** : Microsoft SC-200 (Security Operations Analyst) · TryHackMe SAL1 · ISO/IEC 27001 Foundation

**Contact** : [LinkedIn](https://www.linkedin.com/in/fatima-zahra-rhoulam-25fzrh2004/)
