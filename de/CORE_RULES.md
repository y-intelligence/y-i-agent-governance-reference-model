# Ausgewählter Regelkern

**Version:** v0.1  
**Stand:** 09.09.2026  
**Veröffentlicht:** 11.09.2026
**Autorin:** Nicole Bremicker · Y-Intelligence
**Status:** Kanonische öffentliche Fassung der acht veröffentlichten Regeln

Die acht Regeln konzentrieren sich auf Befugnis, Informationsgrundlage, Ausführung, Übergang und Rechenschaft. Zusammen mit den Definitionen in [GLOSSARY.md](GLOSSARY.md) reichen sie für die Analyse des Falls in [EXAMPLE.md](EXAMPLE.md).

**Leseregel:** „Muss“ und „darf“ kennzeichnen normative Anforderungen innerhalb des Referenzmodells. Beschreibende Aussagen benennen Zusammenhänge; Nachweisgrenzen begrenzen zulässige Schlussfolgerungen. Eine geforderte Invariante ist dadurch weder technisch durchgesetzt noch bewiesen. Die Quellenbezüge nennen fachliche Vorarbeiten, keine Nachweise einer Wirksamkeit von Y-I. Alle Kurzbeispiele gehören zum einzigen veröffentlichten Fall.

## K1 — Befugnis braucht eine anwendbare Grundlage

**Normative Aussage und Geltung:** Eine Aufgabenbefugnis darf nicht weiter reichen als die geltende Rollenbefugnis und deren Mandatsgrundlage. Technischer Zugriff begründet keine zusätzliche Befugnis. Zulässige Autonomie ist begrenzte, kontextgebundene und widerrufbare Delegation; eine gültige Vorabdelegation kann viele Einzelhandlungen abdecken.

**Beispiel:** Die Vorprüfungsrolle darf einen Entwurf speichern. Daraus entsteht kein Versandentscheidungsrecht, auch wenn dieses Speichern technisch einen Versand auslösen kann.

**Nachweisgrenze:** Eine dokumentierte Befugnis beweist weder eine technische Begrenzung noch die rechtliche oder moralische Angemessenheit der zugrunde liegenden Ordnung.

**Nahtstellen:** N1, N3, N5.

**Quellen:** [RBAC](SOURCES.md#rbac); [Overlaying Governance, geprüfte v1](SOURCES.md#overlaying-governance).

## K2 — Kontext muss für die Aussage reichen und dafür zulässig sein

**Normative Aussage und Geltung:** Für die konkret beanspruchte Aussage benötigt eine Rolle sowohl hinreichende Information als auch die Befugnis zu deren Verwendung. Informationsbedarf schafft kein Zugriffsrecht. Zulässige Informationsbeschaffung oder begrenzte Teilarbeit bleibt innerhalb des Mandats möglich.

**Beispiel:** Die freigegebenen Falldaten reichen im Versandfall für den fachlich richtigen Entwurf. Sie begründen keine Versandentscheidung; diese ist eine eigene Befugnisfrage.

**Nachweisgrenze:** Gespeicherte, auffindbare, abgerufene und dem Modell bereitgestellte Inhalte sind verschiedene Zustände. Bereitstellung beweist nicht, dass das Modell die Information sachgerecht genutzt hat. Die im Fall angenommene Hinlänglichkeit ist kein allgemeiner Qualitätsnachweis.

**Nahtstellen:** N2, N3.

**Quellen:** [Sufficient Context, geprüfte v3](SOURCES.md#sufficient-context); [NIST ABAC](SOURCES.md#abac). Die gemeinsame rollen- und aussagebezogene Bedingung ist die hier formulierte Y-I-Zusammenführung.

## K3 — Eine Rollenbindung setzt passende Ausführungsbedingungen voraus

**Normative Aussage und Geltung:** Eine konkrete Instanz muss für die Rollen-Version und Aufgabe qualifiziert und ausdrücklich zugeordnet sein. Zu beurteilen sind die aktuell wirksamen Fähigkeiten und Governance-Bedingungen. Das Binding selbst verleiht keine zusätzlichen Rechte.

**Beispiel:** Die Entwurfsinstanz ist im Fall für Vorprüfung und Entwurf passend gebunden. Diese Zuordnung qualifiziert weder automatisch den Versanddienst noch den gemeinsamen Versandpfad.

**Nachweisgrenze:** Eine vorhandene oder konfigurierte Fähigkeit ist noch kein Nachweis ihrer aktuellen Wirksamkeit. Eine passende Modellwahl belegt auch nicht die korrekte Übersetzung einer fachlichen Bestätigung in einem anderen System.

**Nahtstellen:** N4, N5.

**Quellen:** [Gaia](SOURCES.md#gaia); [Execution Governance 3.0, geprüfte Architekturbasis v0.5.8](SOURCES.md#execution-governance-30).

## K4 — Eine Bestätigung gilt nur für die befugt entschiedene Wirkung

**Normative Aussage und Geltung:** Eine erforderliche Freigabe muss von einer zuständigen Stelle stammen, die konkrete Aktion und ihr Objekt umfassen und bei Wirkungseintritt noch gelten. Sichtbare Bestätigung, technisch wirksamer Grant und tatsächlich durchlaufener Prüfweg müssen dafür unterscheidbar bleiben.

**Beispiel:** „Entwurf fachlich fertig“ bestätigt die Textqualität. Die Prüferin ist im Fall nicht befugt, den Versand zu entscheiden. Ein technisch akzeptierter Status ersetzt diese Entscheidung nicht.

**Nachweisgrenze:** Eine Bestätigungsanzeige belegt die passende Autorisierung nicht ohne Zuständigkeits- und Wirkungsbezug. Ein automatisiertes Prüfsignal kann innerhalb eines gültig autorisierten Regelwerks eine Prüfung beitragen; es erzeugt selbst keine originäre organisationale Entscheidungszuständigkeit.

**Nahtstellen:** N3, N5.

**Quellen:** [How Agents Ask for Permission, geprüfte v2](SOURCES.md#how-agents-ask-for-permission); [AgentBound, geprüfte v2](SOURCES.md#agentbound).

## K5 — Übergänge müssen die Bedeutung der Befugnis erhalten

**Normative Aussage und Geltung:** Bei Übergängen müssen geltende Bedeutungen und Grenzen erhalten bleiben oder befugt geändert werden. Zu betrachten sind auch wirksame Übergänge über gemeinsame Arbeitszustände und nachgelagerte Dienste. Informationsübertragung autorisiert keine zusätzliche Handlung.

**Beispiel:** Der Status „ready“ bedeutet in der Entwurfsanwendung „bereit zur Versandentscheidung“. Der Versanddienst darf daraus nicht „Versand autorisiert“ machen. Er handelt aus eigenem Mandat und muss dessen Voraussetzung einer gültigen Versandentscheidung erfüllen.

**Nachweisgrenze:** Eine Liste direkter Tools oder deklarierter Übergaben zeigt nicht sämtliche erreichbaren Wirkungen. Lokal erfüllte Spezifikationen belegen keine konsistente Zusammensetzung. Ungeklärte Folgepfade tragen keine positive Aussage über durchgehende Kontrolle.

**Nahtstellen:** N5, N6.

**Quellen:** [Execution Governance 2.1, geprüfte v1.1](SOURCES.md#execution-governance-21); [Policies on Paths, geprüfte v1](SOURCES.md#policies-on-paths); [VIGIL, geprüfte v1](SOURCES.md#vigil).

## K6 — Änderung oder Ersatz übernimmt keine ungeprüfte Gültigkeit

**Normative Aussage und Geltung:** Ein technischer Wechsel, ein Ersatzpfad oder der Verlust einer benötigten Fähigkeit darf Befugnisse und Qualifikation nicht stillschweigend als unverändert gültig behandeln. Weiterarbeit, Einschränkung, erneute Beurteilung, Eskalation oder Stopp richten sich nach der betroffenen Aufgabe.

**Beispiel:** Wird im Versandfall die Statusauslegung korrigiert, muss die Beurteilung den geänderten gemeinsamen Pfad erfassen. Die weiterhin passende Entwurfsinstanz allein belegt die Korrektur nicht. Interne Arbeit kann fortgesetzt werden, wenn der unautorisierte mittelbare Versand ausgeschlossen ist.

**Nachweisgrenze:** Wiederherstellung macht vergangene Entscheidungen nicht rückwirkend zulässig. Die Beschreibung eines korrigierten Ablaufs belegt weder seine Implementierung noch seine dauerhafte Wirksamkeit.

**Nahtstellen:** N4, N6.

**Quellen:** [Execution Governance 3.0, geprüfte Architekturbasis v0.5.8](SOURCES.md#execution-governance-30); [MI9, geprüfte v4](SOURCES.md#mi9).

## K7 — Nachweise müssen Erklärung und wirksames Review ermöglichen

**Normative Aussage und Geltung:** Ausführungsnachweise müssen die relevanten Entscheidungen, Bedingungen und Wirkungen gemeinsam zuordnen lassen. Ein zuständiges Forum benötigt Zugang, Verständnis und Beurteilungsbefugnis. Die Vertrauenswürdigkeit hängt auch davon ab, wer Nachweise verändern oder unterdrücken kann; bei folgenreichen Vorgängen kann unabhängige Erfassung oder Bestätigung nötig sein.

**Beispiel:** Das Versandlog wird mit Entwurfsstand, fachlicher Bestätigung, Mandatsgrundlage und Statusauslegung verbunden. Das Forum kann so die Freigabeordnung und deren technische Umsetzung getrennt untersuchen.

**Nachweisgrenze:** Logs und signierte Belege erzeugen für sich genommen keine institutionelle Rechenschaft. Ein benanntes Forum beweist noch kein tatsächlich wirksames Review. Nachweise erfordern keine unbegrenzte Speicherung sämtlicher Inhalte.

**Nahtstelle:** N7.

**Quellen:** [Bovens](SOURCES.md#bovens); [ADOPT](SOURCES.md#adopt); [AgentBound, geprüfte v2](SOURCES.md#agentbound).

## K8 — Governance-Tiefe und Aussagekraft müssen begründet sein

**Normative Aussage und Geltung:** Die erforderliche Tiefe richtet sich nach Wirkung, Autonomie, Befugnisumfang, Datenzugriff und Rücknehmbarkeit. Jede positive Prüfaussage muss ihren Nachweisumfang und ihre verbleibenden Grenzen erkennen lassen.

**Beispiel:** Für den externen Versand ist die gültige Versandentscheidung maßgeblich. Vorprüfungsarbeit kann in einem engeren Rahmen weitergehen, sobald ihre unerlaubte Versandwirkung ausgeschlossen ist. Die bloße Abwesenheit direkter Versandwerkzeuge reicht dafür nicht.

**Nachweisgrenze:** Konzeptionelle Beschreibung, operationalisierte Prüfung, technische Durchsetzung und empirisch belegter Zusatznutzen sind verschiedene Aussagen. Keine folgt allein aus der vorherigen. Das Ausbleiben beobachteter Verstöße beweist keine vollständige Abdeckung. Y-I legt hier keinen universellen Score fest.

**Nahtstellen:** N1 bis N7.

**Quellen:** [NIST AI RMF 1.0](SOURCES.md#nist-ai-rmf); [Execution Governance 3.0, geprüfte Architekturbasis v0.5.8](SOURCES.md#execution-governance-30).
