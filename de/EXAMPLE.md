# Konstruierter Fall: Aus „fachlich fertig“ wird „Versand autorisiert“

**Version:** v0.1  
**Stand:** 09.09.2026  
**Veröffentlicht:** 11.09.2026  
**Autorin:** Nicole Bremicker · Y-Intelligence  

## 1. Charakter des Falls

Der Fall ist eine **vollständig konstruierte analytische Illustration**. Er ist weder ein beobachteter Kundenfall noch ein Implementierungstest.

Ein Logistikunternehmen bearbeitet eine B2B-Reklamation. Die Rolle „Reklamationsvorprüfung“ darf freigegebene Falldaten lesen, den Sachverhalt ordnen und einen Antwortentwurf erstellen. Externe Kommunikation benötigt eine gesonderte Versandentscheidung. Gutschriften und Haftungsentscheidungen gehören nicht zum Auftrag.

Die Informationsgrundlage ist für den Entwurf ausreichend; seine fachliche Richtigkeit und die passende Bindung der Entwurfsinstanz werden angenommen. Die Instanz hat Lese- und interne Schreibrechte, aber keine direkte Sendefunktion. Damit lässt sich der Bedeutungsfehler untersuchen, ohne ihn mit einem Wissens- oder Modellfehler zu vermischen.

## 2. Rollen und Zuständigkeiten

| Beteiligte Stelle oder Komponente | Erlaubte beziehungsweise zugewiesene Funktion |
|---|---|
| **Kundenserviceleitung** | Legt die Vorprüfungsrolle und die organisationale Freigabeordnung fest. |
| **Entwurfsinstanz** | Ordnet Falldaten und erstellt den internen Entwurf. |
| **Fachliche Prüferin** | Bestätigt die fachliche Vollständigkeit; besitzt kein Versandentscheidungsrecht. |
| **Versandentscheiderin** | Darf eine bestimmte externe Nachricht an den vorgesehenen Empfänger unter geltenden Bedingungen autorisieren. |
| **Versanddienst unter eigenem Dienstkonto** | Führt aufgrund seines eigenen Mandats gültige Versandentscheidungen aus. |
| **Technische Betriebsverantwortung** | Verantwortet die technische Umsetzung der Freigabeordnung. |
| **Betrieblich beauftragtes Reviewgremium** | Darf die organisatorischen und technischen Entscheidungen untersuchen und Folgemaßnahmen verlangen. |

Diese Zuständigkeiten sind Fallannahmen, keine allgemeine Organisationsvorschrift.

## 3. Was lokal korrekt abläuft

Die Entwurfsinstanz erstellt den richtigen Text. Die Prüferin bestätigt dessen Qualität in einer zutreffend als Entwurfsprüfung bezeichneten Oberfläche. Die Entwurfsanwendung setzt daraufhin `ready`. Ihre lokale Spezifikation definiert den Status als „Entwurf vollständig; bereit zur Versandentscheidung“.

Der Versanddienst liest denselben Arbeitszustand. Seine technische Spezifikation behandelt `ready` als hinreichenden Freigabestatus. Er verwendet sein korrekt eingerichtetes Dienstkonto und sendet. Damit erfüllt auch er seine lokale technische Spezifikation. Diese bildet jedoch die Voraussetzung seines organisationalen Auftrags falsch ab.

„Lokal korrekt“ bedeutet hier **korrekt relativ zur jeweiligen lokalen Spezifikation**. Es bedeutet keine vollständige Governance-Konformität. Dass lokale Funktionstests bestehen könnten, wird analytisch angenommen; es wurden keine Tests ausgeführt.

## 4. Der semantische Bruch

| Schritt | Belegbare Aussage innerhalb der Fallannahmen | Unzulässiger Schluss |
|---|---|---|
| Fachliche Bestätigung | Die Prüferin hält den Entwurf für fachlich vollständig. | Die zuständige Stelle habe den Versand entschieden. |
| Speicherung von `ready` | Der Entwurf ist bereit für die Versandentscheidung. | Die Versandentscheidung liege bereits vor. |
| Auswertung durch Versanddienst | Der Dienst akzeptiert den Status gemäß seiner technischen Regel. | Diese Regel bilde die organisationale Autorisierung korrekt ab. |
| Versand unter Dienstkonto | Das Konto kann technisch senden; die Nachricht wird verschickt. | Technische Versandberechtigung belege die gültige Entscheidung über diese Nachricht. |

Der Bruch entsteht an **N6 – Ausführung und Governance Transition**: Eine Sachbewertung wird beim Übergang in eine vermeintliche Autorisierung umgedeutet. An **N5 – Authority und Ausführung** wird diese Umdeutung zur tatsächlichen externen Wirkung.

Dabei bleiben drei Ebenen getrennt:

- Die **Approval Presentation** ist die sichtbare Bestätigung der Entwurfsqualität.
- Der **Effective Grant** gestattet dem Dienstkonto technisch den Versand.
- Der **Effective Review Path** enthält tatsächlich Entwurfsprüfung und Statusauswertung, aber keine Prüfung einer gültigen Versandentscheidung.

Der Versanddienst erbt keine Rechte der Entwurfsrolle. Er verfehlt die Bedingung seines eigenen Mandats, weil er ein ungeeignetes Signal als Nachweis verwendet. Auch das Mandat der Entwurfsrolle erweitert sich nicht. Deren Schreibzugriff besitzt jedoch eine mittelbare Versandwirkung, die in der Betrachtung berücksichtigt werden muss.

## 5. Bedingungen einer konzeptionellen Korrektur

Organisatorisch müssen Entwurfsabschluss und Versandentscheidung getrennt sein. Die befugte Versandentscheidung muss die bestimmte Nachricht, ihren Empfänger und die geltenden Bedingungen umfassen. Wesentliche spätere Änderungen verlangen eine entsprechend erneuerte Entscheidung. Die fachliche Prüferin wird durch ihren früheren Klick nicht nachträglich zur Versandentscheiderin.

Technisch muss diese Bedeutung bis zur tatsächlichen Wirkung erhalten bleiben. Ein fertiger Entwurf darf der Entscheidungsstelle vorgelegt werden, ohne dadurch sendbar zu werden. Wo präventive Autorisierung vorgeschrieben ist, muss innerhalb des benannten Nachweisumfangs jeder relevante Weg zum Versand vor Wirkungseintritt wirksam autorisiert oder technisch ausgeschlossen sein. Dazu gehört der hier wirksame Weg über den gemeinsamen Arbeitszustand. Welche technische Lösung dies leistet, ist gesondert zu gestalten und nachzuweisen.

Bis diese Bindung geklärt ist, kann die Vorprüfungsrolle intern weiterarbeiten, sofern ihr mittelbarer Versand ausgeschlossen und der begrenzte Arbeitszustand bestätigt ist. Nach einer Korrektur ist der gemeinsame Pfad beider Ausführungskontexte zu beurteilen.

Das Reviewgremium benötigt den Zusammenhang von Mandat, Rollen-Version, Entwurfsstand, fachlicher Bestätigung, Statusauslegung und Versandereignis. Es kann die Kundenserviceleitung zur Freigabeordnung und die technische Betriebsverantwortung zur Umsetzung befragen. Der bereits erfolgte Versand wird durch eine spätere Freigabe weder ungeschehen noch ursprünglich zulässig. Eine Korrekturkommunikation wäre eine neue, eigens zu autorisierende Handlung.

## 6. Was der Fall zeigt – und was er nicht beweist

Der konstruierte Verlauf zeigt einen möglichen Widerspruch zwischen lokal korrekten Spezifikationen und einer gemeinsamen Governance-Bedingung. Die Begriffe und Regeln des Y-I Referenzmodells beschreiben den Konflikt und die Bedingungen seiner konzeptionellen Korrektur.

Der Fall beweist weder eine erfolgreiche technische Implementierung noch vollständige Pfadabdeckung oder dauerhafte Wirksamkeit. Er belegt auch keinen Vorteil gegenüber anderen Ansätzen bei Verständlichkeit, Fehlererkennung oder Aufwand. Vorhandene Autorisierungs- und Runtime-Governance-Ansätze können denselben Konflikt bei passender organisationaler Semantik ebenfalls ausdrücken.

Siehe den [kanonischen Regelkern](CORE_RULES.md) und die [Definitionen](GLOSSARY.md).
