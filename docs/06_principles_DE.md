# Entwicklungsprinzipien und öffentliche Dokumentation

Diese Prinzipien beschreiben die **Architekturrichtung** der Arbeit an ToF Systems. Sie helfen bei der Bewertung von Entwürfen, sind aber keine Garantie für die Entwicklungsreife jedes öffentlichen Werkzeugs.

## Technische Prinzipien

- Zuständigkeiten und Schnittstellen ausdrücklich voneinander trennen.
- Modulare Komponenten statt eines undurchsichtigen Monolithen bevorzugen.
- Wege von Informationen nachvollziehbar halten.
- Berechtigung, Datenschutz und Schutz als Architekturaufgaben behandeln.
- Generierte LLM-Antworten von überprüften Zuständen oder anerkannten Belegen unterscheiden.
- Laufendes Runtime-Verhalten, archiviertes Material und Pläne eindeutig kennzeichnen.
- Betriebsgrenzen sichtbar machen, auch wenn öffentlich nur ein reduziertes Modell gezeigt wird.

## Prinzipien öffentlicher Dokumentation

- Verständliche Beispiele und Erklärungen veröffentlichen, die ohne Zugang zum privaten System funktionieren.
- Zugangsdaten, private Kennungen, sensible Pfade, Logs und Betreibereingriffe nicht veröffentlichen.
- Entwurf, Prototyp, funktionierendes Werkzeug und verifizierten Betriebsnachweis unterscheiden.
- Für tatsächliche Befehle, Funktionen und Grenzen auf das jeweilige Produkt-Repository verweisen.

## Praktische Bedeutung

Öffentliche Dokumentation soll erklären, *welches Problem ein Prinzip löst*, statt Grenzen nur zu wiederholen. Architekturreferenzen benennen Absichten und Unterscheidungen; ausführbare Repositories liefern die jeweils relevanten Implementierungsnachweise.

[Projekte](../README_DE.md) · [Öffentliche Grenzen](09_boundaries_DE.md)
