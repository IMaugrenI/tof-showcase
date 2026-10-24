# ToF Systems — Architekturüberblick

**ToF Systems** verbindet eigenständige Local-First-Werkzeuge, KI-gestützte Entwicklungsabläufe und Architekturarbeit mit dem Schwerpunkt auf klaren Zuständigkeiten, kontrollierten Datenflüssen und überprüfbaren Ergebnissen.

Dieses Dokument erläutert die **Architekturideen** der übergreifenden Entwicklungsarbeit. Praktisch nutzbare öffentliche Beispiele findest du in der [Projektübersicht](../README_DE.md).

## Zwei unterschiedliche Aufgaben der früheren Architektur

Ältere ToF-Dokumente verwenden die Bezeichnung **ToF / V’eth**. In dieser Architektur stehen die Namen für verschiedene Verantwortlichkeiten:

- **ToF:** technische Struktur, Verarbeitung, Aufgabentrennung und operative Kontrollen.
- **V’eth:** Identität, Spiegelung und Ausdruck — wie das System nach außen erscheint und kommuniziert.

Die Trennung ist wichtig: Eine Gesprächsidentität oder ein Darstellungsstil darf nicht allein deshalb technische Autorität bekommen, weil sie zu demselben Assistenten gehören. Die historischen Bezeichnungen sind keine Voraussetzung, um die heutigen öffentlichen Projekte zu verstehen.

## Architekturprinzipien

- Zuständigkeiten trennen statt Funktionen unkontrolliert zu vermischen.
- Datenbewegungen und Entscheidungen nachvollziehbar halten.
- Plattformspezifische Adapter am Rand belassen.
- Gespeicherte Referenzen, historische Belege und aktuellen Runtime-Zustand unterscheiden.
- Einwilligung, Berechtigung und Schutz durch ausdrücklich definierte Mechanismen behandeln.
- Öffentliche Beschreibungen von Nachweisen tatsächlich umgesetzter oder laufender Funktionen trennen.

## Was diese Dokumentation zeigt

Das Showcase enthält Architekturerklärungen, Prinzipien und reduzierte Beispiele. Es veröffentlicht **nicht** das gesamte private System und beweist **nicht**, dass jede Architekturidee bereits umgesetzt wurde.

Die öffentlichen Werkzeuge — [Container Pulse](https://github.com/IMaugrenI/tof_container_pulse), [Local Knowledge](https://github.com/IMaugrenI/tof_local_knowledge), [Local Builder](https://github.com/IMaugrenI/tof_local_builder) und [Local Case Organizer](https://github.com/IMaugrenI/local_case_organizer) — dokumentieren ihren jeweiligen tatsächlichen Funktionsumfang und die eigene Einrichtung.

[Weiter: Technische Architektur](02_what-is-tof_DE.md) · [Projektkontext](06_project-line_DE.md)
