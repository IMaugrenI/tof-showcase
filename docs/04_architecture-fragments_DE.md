# Systemarchitektur — Öffentlicher Überblick

Die frühere ToF-Architektur beschreibt **getrennte Zuständigkeiten** statt eines einzigen Bot-Prozesses. Dieses Dokument zeigt bewusst eine reduzierte konzeptionelle Sicht und kein vollständiges Deployment-Diagramm.

## Aufgabenbereiche der Verarbeitung

- **Eingang und Annahme:** Material über kontrollierte Eingänge aufnehmen.
- **Prüfung und Filterung:** grundlegende Gültigkeit und Kontext klären.
- **Governance und Schutz:** Berechtigungen, Sicherheits- und Entscheidungsgrenzen berücksichtigen.
- **Analyse und Verarbeitung:** angenommene Eingaben interpretieren und bearbeiten.
- **Zustand und Aufbewahrung:** aktuellen State von gespeicherten Aufzeichnungen trennen.
- **Archivierung:** Historie und Herkunft sichern.
- **Ausgabevorbereitung und Auslieferung:** Antworten vorbereiten, ohne generierten Text zur Systemwahrheit zu erklären.

Das sind Zuständigkeitsgruppen. Sie bedeuten nicht, dass jede Gruppe exakt einem Dienst, Container oder überall produktiv betriebenen Schritt entspricht.

## Plattformlogik an den Rand

Externe Plattformen verwenden eigene Ereignisse und Nachrichtenformate. Adapter übersetzen diese Eingaben in interne Darstellungen, damit die Plattform nicht den technischen Kern bestimmt.

## Nachweis und Umfang

Die Architekturübersicht lässt private Runtime-Pfade, Betreiberabläufe, Dienstkonfiguration und sicherheitskritische Details bewusst aus. Für tatsächlich nutzbare Implementierungen sind [die öffentlichen Produkt-Repositories](../README_DE.md) maßgeblich, nicht diese konzeptionelle Skizze.

[Verarbeitungskette](05_public-chain_DE.md) · [Ebenengrenzen](03_layer-separation_DE.md)
