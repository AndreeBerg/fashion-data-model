# GS1 Fashion Data model

Dieses Repository enthält alle notwendigen Informationen für die Modeindustrie um einen Datenaustausch im GS1 Fashion Datenmodell zu implementieren.

# Motivation

Die GS1 möchte den Teilnehmern in der Modeindustrie den Datenaustausch erleichtern. Schneller Produktionszyklen, eine größere Anzahl an Datenaustauschpartnern und die immer größere Wichtigkeit von Produktdaten in Zeiten des E-Commerce erfordern einen reibungslosen Datenaustausch. Durch die Vereinbarung eines Standards wird sichergestellt, dass innerhalb der Modeindustrie eine einheitliche "Sprache" gesprochen wird.
Der Fokus wurde auf eine einfache Verwendung und Implementierung gelegt, ebenso auf die Bedürfnisse der Internationalisierung und der damit verbundenen Mehrsprachigkeit der Daten.

# Inhalt

-   Datenmodellbeschreibung in Google Sheets
-   JSON Schema zur Validierung von JSON Nachrichten
-   JSON Beispiel Datensatz

Das vorliegende Syntax neutrale Excel Pilot Datenmodell ist in Zusammenarbeit mit den Unternehmen Ahlers Group, Hagemeyer, Zalando, KATAG, Falke und Fashion Cloud erstellt worden.

-   In Sope 1 der Umsetzung liegt die Konzentration auf die Attribute die Stand heute vom Datensender geliefert werden können.

-   In Sope 2-n ist eine Erweiterung um Attribute geplant die für Online benötigt werden.

-   Ziel ist es, dem Datensender einen Überblick über zukünftige Anforderungen zu geben, die er dann mit entsprechenden Zeitpuffer in seine internen Prozesse umsetzen kann.

### Das Excel Pilotdatenmodell ist wie folgt aufgebaut:

-   Es dient als Basis Information mit allen von der Branche bisher und zukünftig definierten Attribute

-   Filterung in Spalte M auf Scope 1 mit 59 Attributen für den Start in den elektronischen Datenaustausch

Da die Fashion Branche technologisch unabhängig sein möchte, haben wir versucht mehrere Kommunikationsstandards abzubilden, welches nun mit aktiven Piloten live getestet werden soll. Im Detail sind das:

-   Definition der Attribute die PRICAT übermittelt werden können (Spalte P-R)

-   Eine Beschreibung des Aufbaus der JSON Blaupause als Schema und eine Dokumentation wie daraus eine api Schnittstellenbeschreibung erstellt werden kann

-   Eine Dokumentation wie für diese 59 Attribute ebenfalls eine XML API Schnittstellenbeschreibung erstellt werden kann
