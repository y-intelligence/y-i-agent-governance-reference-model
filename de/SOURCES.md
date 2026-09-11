# Quellen und Related Work

**Version:** v0.1  
**Versionsstand der Quellenprüfung:** 09.09.2026

## Versionslogik

Fachliche Aussagen in diesem Repository beziehen sich auf die jeweils ausdrücklich benannte Fassung. Eine neuere Fassung wird nicht stillschweigend als identisch mit der untersuchten Fassung behandelt.

- **arXiv:** Die geprüfte Revisionsnummer wird angegeben und versioniert verlinkt.
- **Zenodo:** Verwendet wird der DOI beziehungsweise Record der konkret geprüften Version. Spätere Records werden separat ausgewiesen.
- **Zeitschriften und institutionelle Veröffentlichungen:** Verlinkt werden DOI und, soweit sinnvoll, die offizielle Publikationsseite.
- **Working Papers und selbst veröffentlichte Arbeiten:** Der Publikationsstatus wird ausdrücklich benannt. Er ist weder ein Wirksamkeitsnachweis noch eine Abwertung des fachlichen Inhalts.

Das Verzeichnis dokumentiert die für v0.1 tatsächlich verwendete Auswahl. Es beansprucht keine vollständige systematische Literaturübersicht.

## Historische und institutionelle Grundlagen

### RBAC

Sandhu, R. S., Coyne, E. J., Feinstein, H. L., & Youman, C. E. (1996). *Role-Based Access Control Models*. **Computer, 29**(2), 38–47. Journalartikel. [DOI 10.1109/2.485845](https://doi.org/10.1109/2.485845).

**Bezug in v0.1:** Rollenbezogene Autorisierung und begrenzende Berechtigungsstrukturen.

### ABAC

Hu, V. C., Ferraiolo, D., Kuhn, D. R., Schnitzer, A., Sandlin, K., Miller, R., & Scarfone, K. (2014; aktualisierte amtliche Ausgabe 02.08.2019). *Guide to Attribute Based Access Control (ABAC) Definition and Considerations*. NIST SP 800-162. Institutionelle Veröffentlichung. [NIST-Publikation](https://csrc.nist.gov/pubs/sp/800/162/upd2/final); [DOI 10.6028/NIST.SP.800-162](https://doi.org/10.6028/NIST.SP.800-162).

**Geprüfter Umfang:** Amtliche Metadaten und Grunddefinition im Abstract; kein erneuter Volltextvergleich sämtlicher Abschnitte.

### Gaia

Wooldridge, M., Jennings, N. R., & Kinny, D. (2000). *The Gaia Methodology for Agent-Oriented Analysis and Design*. **Autonomous Agents and Multi-Agent Systems, 3**, 285–312. Journalartikel. [DOI 10.1023/A:1010071910869](https://doi.org/10.1023/A:1010071910869).

**Bezug in v0.1:** Multi-Agenten-System als rechnergestützte Organisation mit interagierenden Rollen; Verbindung von Rollen, Verantwortlichkeiten und Berechtigungen.

### ADOPT

Baldoni, M., Baroglio, C., May, K. M., Micalizio, R., & Tedeschi, S. (2018). *Computational Accountability in MAS Organizations with ADOPT*. **Applied Sciences, 8**(4), Artikel 489. Journalartikel. [DOI 10.3390/app8040489](https://doi.org/10.3390/app8040489).

**Bezug in v0.1:** Rollenannahme, institutionelle Befugnisse und Rechenschaft in Multi-Agenten-Organisationen.

### Bovens

Bovens, M. (2007). *Analysing and Assessing Accountability: A Conceptual Framework*. **European Law Journal, 13**(4), 447–468. Journalartikel. [DOI 10.1111/j.1468-0386.2007.00378.x](https://doi.org/10.1111/j.1468-0386.2007.00378.x).

**Bezug in v0.1:** Rechenschaft als Beziehung zwischen erklärungspflichtigem Akteur und beurteilungs- sowie folgenbefugtem Forum.

### NIST AI RMF

Tabassi, E. (2023). *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*. NIST AI 100-1, veröffentlicht am 26.01.2023. Institutionelles Framework. [NIST-Publikation](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-ai-rmf-10); [DOI 10.6028/NIST.AI.100-1](https://doi.org/10.6028/NIST.AI.100-1).

**Bezug in v0.1:** Risikobezogene Angemessenheit und institutionelle Governance-Funktionen. Das Y-I Referenzmodell ist selbst kein NIST-Standard.

## Kontext und aktuelle Agent-Governance-Arbeiten

### Sufficient Context

Joren, H., Zhang, J., Ferng, C.-S., Juan, D.-C., Taly, A., & Rashtchian, C. (2025). *Sufficient Context: A New Lens on Retrieval Augmented Generation Systems*. arXiv:2411.06037v3, Revision vom 23.04.2025; Erstfassung vom 09.11.2024. ICLR 2025; für die vorliegende Prüfung wurde arXiv v3 herangezogen. [Geprüfte v3](https://arxiv.org/abs/2411.06037v3).

**Geprüfter Umfang:** Metadaten und Abstract der v3 für die Unterscheidung zwischen hinreichender Informationsbasis und tatsächlicher Modellnutzung. Die Arbeit wird nicht als Quelle für organisationale Autorisierung ausgegeben.

### AgentBound

Kaul, A., Lan, Q., & Gupta, P. (2026). *Behavioral Governance for Autonomous AI Agents: The AgentBound Framework*. arXiv:2606.30970v2, Revision vom 01.07.2026; Erstfassung vom 29.06.2026. Preprint. [Geprüfte v2](https://arxiv.org/abs/2606.30970v2).

**Geprüfter Umfang:** Abschnitte 3–7 und 10 der v2. Verwendet werden insbesondere die konservative Komposition von Autorisierungsentscheidungen, die fehlende befugniserweiternde Wirkung eines Reviews und handlungsbezogene Governance-Nachweise. Architektur- und Benchmarkbeschreibung werden nicht als unabhängig bestätigte Implementierung oder Evaluation behandelt.

### Overlaying Governance

Ibrahim, A., & Li, Y. (2026). *Overlaying Governance: A Compositional Authorization Framework for Delegation and Scope in Agentic AI*. arXiv:2606.03518v1, 02.06.2026. Preprint. [Geprüfte v1](https://arxiv.org/abs/2606.03518v1).

**Geprüfter Umfang:** Abschnitte 3–5. Verwendet werden Ausgangsberechtigung, Delegation, Scope und begrenzter Handlungsspielraum. Die Arbeit beschreibt formale Eigenschaften und eine Erprobung unter benannten Annahmen; daraus wird kein allgemeiner Wirksamkeitsnachweis abgeleitet.

### Execution Governance 3.0

Ku, H. W. (2026). *Execution Governance 3.0: From Pre-Effect Authorization to Authorization-Bound Execution*. Architektur v0.5.8, 10.08.2026. Selbst veröffentlichte Forschungsarchitektur, Zenodo. [DOI 10.5281/zenodo.21873291](https://doi.org/10.5281/zenodo.21873291).

**Geprüfter Umfang:** PDF-Volltext der Architekturbasis v0.5.8, insbesondere Abschnitte 6.4, 12–13, 15–17 und 26.1. Inhaltliche Aussagen in v0.1 bleiben an diese Architekturbasis gebunden.

**Spätere Versionen:** v0.5.8.1 vom 12.08.2026 ([DOI 10.5281/zenodo.21903244](https://doi.org/10.5281/zenodo.21903244)) und v0.5.8.2 vom 06.09.2026 ([DOI 10.5281/zenodo.22524986](https://doi.org/10.5281/zenodo.22524986)) wurden für die Versions- und Update-Erklärung herangezogen. Ihre zusätzlichen Versuchsbehauptungen wurden nicht unabhängig reproduziert und werden nicht rückwirkend der geprüften v0.5.8-Basis zugeschrieben.

### Execution Governance 2.1

Ku, H. W. (2026). *Execution Governance 2.1: Continuity Drift Detection in Autonomous Systems*. White Paper v1.1, 23.04.2026. Selbst veröffentlichte konzeptionelle Architektur, Zenodo. [DOI 10.5281/zenodo.19713109](https://doi.org/10.5281/zenodo.19713109).

**Geprüfter Umfang:** PDF-Volltext, insbesondere Abschnitte 2–5 und 10.6. Verwendet werden Kontinuitätsdrift und semantische Abweichung trotz lokal gültig erscheinender Ausführung.

### Policies on Paths

Kaptein, M., Khan, V.-J., & Podstavnychy, A. (2026). *Runtime Governance for AI Agents: Policies on Paths*. arXiv:2603.16586v1, 17.03.2026. Preprint. [Geprüfte v1](https://arxiv.org/abs/2603.16586v1).

**Geprüfter Umfang:** Abschnitte 3–4 und 6. Verwendet werden pfadbezogene Runtime-Prüfung und die ausdrückliche Freigabebedingung vor einer Versandwirkung. Die diskutierte Referenzimplementierung wird nicht als verifiziertes deploybares Gesamtsystem behandelt.

### VIGIL

Li, Y., Chen, Y., Wen, H., Zhang, B., Liu, H., Wang, P., Feng, Y., & Tian, Y. (2026). *VIGIL: Runtime Enforcement of Behavioral Specifications in AI Agent Skills*. arXiv:2606.26524v1, 25.06.2026. Preprint. [Geprüfte v1](https://arxiv.org/abs/2606.26524v1).

**Geprüfter Umfang:** Abschnitte III–VII. Verwendet werden zeitliche, objektbezogene und pfadübergreifende Beziehungen. Die berichtete Evaluation wird nicht zu einem allgemeinen Governance-Nachweis erweitert.

### How Agents Ask for Permission

Michael, A. E., & Roesner, F. (2026). *How Agents Ask for Permission: User Permissions for AI Agents, from Interfaces to Enforcement*. arXiv:2607.13718v2, Revision vom 20.07.2026; Erstfassung vom 15.07.2026. Preprint. [Geprüfte v2](https://arxiv.org/abs/2607.13718v2).

**Geprüfter Umfang:** Abschnitte 3–6. Verwendet werden die Trennung von Berechtigungsdarstellung, interner Repräsentation, Ableitung und Durchsetzung sowie die Analyse automatisierter Review-Pfade. Produktbefunde gelten nur für die untersuchten Ausführungen und Zeitpunkte.

### MI9

Wang, C. L., Singhal, T., Kelkar, A., & Tuo, J. (2025). *MI9: An Integrated Runtime Governance Framework for Agentic AI*. arXiv:2508.03858v4, Revision vom 18.11.2025; Erstfassung vom 05.08.2025. **Trustworthy Agentic AI Workshop @ AAAI 2026** am 27. Januar 2026 veröffentlicht. [Geprüfte v4](https://arxiv.org/abs/2508.03858v4).

**Geprüfter Umfang:** Abschnitt 4. Verwendet werden integrierte Runtime-Governance, Autorisierung, Zustandskonformität, Beobachtung und abgestufte Eindämmung. Ein im Abstract formulierter Erstmaligkeitsanspruch wird nicht übernommen.

### Scalable Runtime Governance

Szpruch, L., Sudjianto, A., Bhatti, T., & Ang, G. (2026). *Scalable Runtime Governance for Agentic AI in Financial Services*. SSRN Working Paper, SSRN 6567199; als Preprint registriert. [DOI 10.2139/ssrn.6567199](https://doi.org/10.2139/ssrn.6567199).

**Zugangs- und Aussagegrenze:** Für den zugrunde liegenden Vergleich lag kein geprüfter Volltext vor. Metadaten, Abstract-/Indexinformationen und eine Autorenbeschreibung ersetzen keinen Volltextvergleich. Deshalb bleibt offen, inwieweit die Arbeit aufgabenbezogene Kontext-Hinlänglichkeit, Rollen- oder Capability-Qualifikation, Freigabesemantik und institutionelle Rechenschaft in einer gemeinsam referenzierten Struktur integriert.

## Verdichtete Einordnung

| Arbeitsrichtung | Relevante Überschneidung | Abgrenzung der Aussage in v0.1 |
|---|---|---|
| Rollen- und Organisationsmodelle | Rollen, Verantwortlichkeiten, Berechtigungen und Rechenschaft | Y-I wendet diese Beziehungen auf wechselnde technische Instanzen und konkrete Wirkungen an; die Rollenidee selbst ist nicht neu. |
| RBAC und ABAC | Rollen- und attributbezogene Autorisierung | Y-I behandelt zusätzlich Mandatsquelle, Aussagekontext, Ausführungsbindung, Übergang und institutionelles Review in einer gemeinsamen rollenbezogenen Betrachtung. |
| Integrierte Runtime-Governance | Autorisierung, aktuelle Bedingungen, Ausführungspfade, Kontinuität und Nachweise | Dies sind enge Vorarbeiten. Y-I beansprucht keinen Vorrang und keine nachgewiesene Überlegenheit. |
| Permission- und Enforcement-Arbeiten | Darstellung, Ableitung, Durchsetzung sowie zeitliche und objektbezogene Pfadbedingungen | Y-I expliziert besonders die organisationale Entscheidungszuständigkeit und ihren Bezug zur konkret ausgelösten Wirkung. |

Der begründbare Y-I-Beitrag bleibt damit eine **rollenbezogene Synthese und Explikation etablierter Governance-Anforderungen**. Die genaue Restdifferenz gegenüber eng verwandten integrierten Ansätzen bleibt offen.
