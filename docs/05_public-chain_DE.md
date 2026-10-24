# Verarbeitungskette — Reduziertes Architekturmodell

Diese Referenz zeigt eine **konzeptionelle Reihenfolge von Zuständigkeiten** aus früherer ToF-Architekturarbeit. Sie ist weder eine verifizierte Karte einer laufenden Installation noch eine Vorgabe für jedes öffentliche Werkzeug.

## Vereinfachte Abfolge

1. Eingang
2. Edge / Annahme
3. Prüfung
4. Governance / Entscheidung
5. Safety / Schutz
6. Analyse
7. Verarbeitung
8. State
9. Retention
10. Archiv
11. Vector / Kohärenzraum
12. Ausgabevorbereitung
13. Ausgabe

Die Liste bewahrt die Unterscheidungen des früheren Architekturmodells. Sie ist kein Beweis für dreizehn einzelne Container, eine starre Echtzeitreihenfolge aller Nachrichten oder bereits vollständig umgesetztes Verhalten.

## Warum diese Reihenfolge wichtig ist

Das Grundprinzip lautet: Eingehende Informationen sollen geprüft und anhand klarer Regeln behandelt werden, bevor Entscheidungen oder Antworten entstehen. Historische Aufzeichnungen und aktueller Zustand haben unterschiedliche Rollen. Ein LLM kann die spätere Verarbeitung oder Formulierung unterstützen, doch seine Ausgabe ist **nicht** automatisch eine vertrauenswürdige Quelle oder Berechtigungsentscheidung.

## Was nicht gezeigt wird

Interne Routing-Regeln, Betreibereingriffe, Produktivadressen und vollständige Sicherheitsmechanismen bleiben außerhalb dieser öffentlichen Zusammenfassung.

[Architekturüberblick](04_architecture-fragments_DE.md) · [Technische Leitplanken](07_public-principles_DE.md)
