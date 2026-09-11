# Y-I Referenzmodell für Agent Governance

**Version:** v0.1  
**Stand:** 09.09.2026  
**Veröffentlicht:** 11.09.2026
**Autorin:** Nicole Bremicker · Y-Intelligence
**Art:** Konzeptionelle und normative Referenz

---

***Für meinen Vater.***
*Von dir habe ich die Begeisterung für Technik, die Freude am Basteln und die Neugier darauf geerbt, wie Dinge funktionieren.*

*Dieses Modell ist dir gewidmet.*

---

## 1. Zweck und Positionierung

Ein KI-Agent erstellt einen Antwortentwurf. Eine Mitarbeiterin bestätigt: fachlich fertig. Eine nachgelagerte Anwendung versteht diese Bestätigung als Versandfreigabe und verschickt die Nachricht. Der Text kann richtig sein, das Dienstkonto korrekt eingerichtet und jede Komponente ihrer eigenen Spezifikation folgen. Trotzdem fehlt die gültige Entscheidung, diese Nachricht zu versenden.

Das **Y-I Referenzmodell für Agent Governance** behandelt solche Beziehungen zwischen organisationalem Auftrag und tatsächlicher agentischer Ausführung. Agentische Arbeitssysteme verbinden Menschen, Regeln und technische Komponenten, die Aufgaben mit variabler Ausführungsplanung bearbeiten. Governance bestimmt dabei, wer welche Handlungen unter welchen Bedingungen veranlassen darf, wie Änderungen geregelt werden und wer darüber Rechenschaft schuldet.

Mit **Referenzmodell** ist eine strukturierte Beschreibung relevanter Gegenstände, Beziehungen und Gestaltungsanforderungen gemeint. Y-I führt etablierte Governance-Anforderungen konkret rollenbezogen zusammen und erläutert ihre Zusammenhänge.

Der zulässige Beitragsclaim ist bewusst eng:

> Y-I ordnet etablierte Governance-Anforderungen konsequent um die governance-gebundene Rolle und expliziert den gemeinsamen Bezug von Auftrag, Kontext, Aufgabenbefugnis, Ausführungsbedingungen, tatsächlicher Wirkung und institutioneller Rechenschaft.

Die Referenz richtet sich an Menschen, die agentische Arbeitssysteme fachlich verantworten, gestalten oder beurteilen: Prozessverantwortliche, Governance-Verantwortliche, technische Teams und beratende Fachpersonen, insbesondere auch in kleinen und mittleren Unternehmen.

Die leitende Gestaltungsfrage lautet:

> Wie bleiben Auftrag, Befugnis, zulässiger Kontext, tatsächliche Wirkung und Rechenschaft aufeinander bezogen, wenn Aufgaben zwischen Menschen, KI-Instanzen und Anwendungen wechseln?

## 2. Primäre Betrachtungseinheit

### Governance-gebundene Agentenrolle

Die **Agentenrolle** ist eine identifizierbare organisationale Funktion mit bestimmtem Zweck und geregelten Beziehungen. Ihr **Mandat** ist der befugte organisationale Akt beziehungsweise dessen nachvollziehbare Festlegung: Es bestimmt Auftrag, Befugnisse, Grenzen und Verantwortungsbeziehungen. Rolle und Mandat sind deshalb verschiedene Gegenstände.

Eine Rolle kann mehrere konkrete Aufgaben tragen und durch unterschiedliche technische Instanzen ausgeführt werden. Das verwendete Modell, die laufende Sitzung oder der Name eines Dienstkontos erklären für sich genommen weder den Auftrag noch die Entscheidungszuständigkeit. Die Rolle dient als gemeinsamer Bezugspunkt über solche Ausführungswechsel hinweg. Ihre Spezifikation wird versioniert, damit Änderungen erkennbar bleiben. Auch ihre Befugnisse dürfen verändert werden, wenn die dafür zuständige Stelle dies gültig festlegt.

Eine dauerhafte Rollenbeschreibung ist nicht für jede kurze Einzelaufgabe erforderlich. Wo eine unmittelbar aufgabenbezogene Berechtigungsbeschreibung ausreicht, muss zusätzlicher Strukturierungsaufwand begründet sein. Ebenso setzt Y-I keine feste Agentenhierarchie oder vollständig vorab bestimmte Arbeitsteilung voraus.

Die verwendeten Begriffe sind in [GLOSSARY.md](GLOSSARY.md) konsolidiert.

## 3. Fünf Governance-Beziehungen

| Beziehung | Was zusammengehört | Gestaltungsanforderung |
|---|---|---|
| **Begründung** | Mandatsquelle, Mandat, Rolle und Aufgabe | Die konkrete Befugnis bleibt auf eine anwendbare organisationale Grundlage zurückführbar. |
| **Bedingung** | Rolle, Aufgabe, Kontext und Befugnis | Hinreichende Information und zulässige Handlung sind jeweils für die konkrete Aufgabe zu bestimmen. |
| **Bindung** | Rollen-Version, Aufgabe und technische Instanz | Die Ausführung erfolgt durch eine für diese Aufgabe qualifizierte Instanz unter benannten Bedingungen. |
| **Übergang** | Beteiligte, Ausführungen und Governance-Zustände | Bedeutungen und Grenzen bleiben erhalten oder werden durch eine befugte Entscheidung verändert. |
| **Nachweis und Review** | Ausführung, Nachweise, Akteur und Forum | Zusammengehörige Nachweise tragen Erklärung, Beurteilung und begründete Folgemaßnahmen. |

Dies ist keine lineare Prozesskette. Neue Informationen können eine Aufgabe verändern; ein Review kann eine Mandatsänderung veranlassen. Zusätzliche Information oder ein technischer Zustandswechsel erzeugt dabei für sich genommen keine zusätzliche Befugnis.

## 4. Decision Legitimation

**Decision Legitimation** bezeichnet im Y-I-Kontext die Frage nach der **begründbaren Zulässigkeit einer konkreten Entscheidung und ihrer Umsetzung**:

> Wer darf gerade diese Wirkung veranlassen, auf welcher Grundlage und unter welchen aktuellen Bedingungen?

Der Begriff führt die fünf Governance-Beziehungen auf eine konkrete Entscheidung und Wirkung zusammen. 

## 5. Fünf unterscheidbare Zuständigkeiten

| Funktion | Aufgabe im Governance-Zusammenhang |
|---|---|
| **Mandatsquelle** | Legt den Auftrag innerhalb ihrer nachprüfbaren organisationalen Zuständigkeit fest. |
| **Entscheidungs- oder Freigabestelle** | Autorisiert eine konkrete Wirkung oder eine begrenzte Klasse von Wirkungen. |
| **Technische Ausführungsidentität** (*Execution Principal*) | Identität, unter der ein System die Handlung ausführt, etwa ein Dienstkonto. |
| **Rechenschaftspflichtiger Akteur** | Erklärt seine Entscheidungen und organisatorischen oder technischen Vorkehrungen. |
| **Rechenschaftsforum** (*Accountability Forum*) | Darf Erklärungen verlangen, beurteilen und Folgemaßnahmen veranlassen. |

Eine Person kann mehrere Funktionen übernehmen. Ihre jeweiligen Befugnisse und mögliche Interessenkonflikte müssen trotzdem unterscheidbar bleiben. Diese Zuordnung bestimmt keine persönliche rechtliche Haftung.

## 6. Sieben Nahtstellen

Eine **Nahtstelle** ist eine Beziehung, an der unterschiedliche Darstellungen derselben Governance-Anforderung zusammenpassen müssen.

| Nr. | Nahtstelle | Zentrale Frage |
|---|---|---|
| N1 | **Mandatsquelle und Rolle** | Ist der Rollenauftrag einschließlich seiner Grenzen gültig beauftragt? |
| N2 | **Rolle und Kontext** | Reicht die zulässige Informationsgrundlage für die konkret beanspruchte Aussage? |
| N3 | **Aufgabe und Effective Authority** | Welche Handlungen sind unter den aktuellen Aufgabenbedingungen erlaubt, und wer darf sie autorisieren? |
| N4 | **Rolle und Runtime Binding** | Welche Instanz darf diese Rollen-Version für diese Aufgabe unter welchen wirksamen Bedingungen ausführen? |
| N5 | **Authority und Ausführung** | Entspricht die technisch ausgelöste Wirkung der tatsächlich geltenden Befugnis? |
| N6 | **Ausführung und Governance Transition** | Bleibt die Bedeutung beim Zustands- oder Kontrollwechsel erhalten, oder wird sie gültig geändert? |
| N7 | **Evidence und Forum** | Können zuständige Stellen anhand zusammengehöriger Nachweise Entscheidungen, Umsetzung und Folgen beurteilen? |

Bei N3 stammt Befugnis aus der organisationalen Berechtigungsgrundlage. Technische Fähigkeit betrifft die Machbarkeit. Bei N5 zählt auch eine Wirkung, die erst ein nachgelagerter Dienst auslöst. N7 verlangt einen gemeinsamen Entscheidungs- und Wirkungsbezug: Ein Freigabefeld, ein Dienstkonto und ein Versandlog beantworten noch nicht, ob eine befugte Stelle genau diese Nachricht autorisiert hat.

Die kanonische öffentliche Fassung der acht Regeln und ihre Zuordnung zu diesen Nahtstellen steht in [CORE_RULES.md](CORE_RULES.md). Der Konflikt an N5 und N6 wird in [EXAMPLE.md](EXAMPLE.md) durchgehend ausgearbeitet.

## 7. Status, Geltungsbereich und Grenzen

v0.1 ist eine kompakte konzeptionelle Referenz mit normativen Gestaltungsanforderungen. Sie beschreibt Governance-Gegenstände und Beziehungen, die bei der Gestaltung und Beurteilung agentischer Arbeitssysteme gemeinsam betrachtet werden sollen.

Dabei sind fünf Aussageebenen zu unterscheiden:

1. **Konzeptionelle Beschreibung:** benennt Gegenstände, Beziehungen und relevante Fragen.
2. **Operationalisierung:** übersetzt diese Beschreibung in ein anwendbares Vorgehen, Kriterien oder Prüfschritte.
3. **Technische Durchsetzung:** implementiert ausgewählte Bedingungen in konkreten Systemen und Ausführungspfaden.
4. **Validierung:** prüft definierte Aussagen innerhalb eines begrenzten Nachweisumfangs.
5. **Empirisch belegter Zusatznutzen:** zeigt vergleichend, ob eine Anwendung beispielsweise Verständlichkeit oder Fehlererkennung verbessert oder Aufwand reduziert.

Keine dieser Ebenen folgt automatisch aus der vorherigen. Für v0.1 sind die konzeptionelle Beschreibung und ein ausgewählter normativer Regelkern veröffentlicht. 

Offen bleiben unter anderem vollständige Regeln zur Auflösung widersprüchlicher Mandate, eine einheitliche Zeitsemantik, der Umgang mit unvollständiger Beobachtbarkeit und die umfassende Behandlung kumulativer Wirkungen. Auch eine konsistente und technisch korrekt durchgesetzte Mandatsordnung kann unangemessen sein; rechtliche Zulässigkeit, moralische Rechtfertigung, Interessen Betroffener und die Unabhängigkeit eines Forums verlangen eigenständige Beurteilung.

## 8. Related Work und begründbarer Synthesebeitrag

Rollen, institutionelle Befugnis und Rechenschaft sind etablierte Gegenstände. Gaia verbindet Rollen mit Verantwortlichkeiten und Berechtigungen; ADOPT verbindet Rollenannahme und Rechenschaft in Multi-Agenten-Organisationen. RBAC und ABAC strukturieren rollen- beziehungsweise attributbezogene Autorisierung. NIST AI RMF ordnet risikobezogene Governance-Funktionen auf institutioneller Ebene.

Aktuelle Arbeiten reichen bis in die Ausführungsebene: Execution Governance behandelt Kontinuität und autorisierungsgebundene Ausführung; AgentBound verbindet delegierte Autorisierung, Verhaltensregeln und handlungsbezogene Nachweise; Policies on Paths und VIGIL betrachten Ausführungspfade beziehungsweise zeitliche und objektbezogene Beziehungen; Overlaying Governance modelliert Delegation und Scope; MI9 integriert Laufzeitbeobachtung, Autorisierung und abgestufte Reaktionen. Die Permission-Taxonomie von Michael und Roesner trennt unter anderem Darstellung, interne Repräsentation und Durchsetzung von Berechtigungen.

Y-I beansprucht diese Einzelprinzipien nicht als neu. Sein begründbarer Beitrag ist die rollenbezogene Synthese und Explikation ihres gemeinsamen Bezugs auf Auftrag, Aussagekontext, Aufgabenbefugnis, Ausführungsbedingungen, konkrete Wirkung und institutionelle Rechenschaft. Die genaue Restdifferenz gegenüber den engsten integrierten Ansätzen bleibt offen. Die Quellen, geprüften Fassungen und Publikationsstatus sind in [SOURCES.md](SOURCES.md) dokumentiert.
