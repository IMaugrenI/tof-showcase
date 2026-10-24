# ToF Systems — Projekte & Architektur

<p align="center">
  <img src="https://raw.githubusercontent.com/IMaugrenI/IMaugrenI/main/assets/banner/ToF_Banner.png" alt="ToF Systems Banner" width="100%" />
</p>

**Lokale Software, selbst gehostete KI und klar abgegrenzte Systeme.**

Dieses Repository ist der öffentliche Wegweiser durch die Projektfamilie von ToF Systems. Es zeigt, was die einzelnen Werkzeuge leisten, wie ihre Architekturideen zusammenhängen und wo praktische Beispiele liegen. Es ist eine **Übersicht**, keine Produktinstallation und kein Spiegel einer privaten Runtime.

[English](README.md) · [Einstieg](START_HERE_DE.md) · [Dokumentationsindex](docs/INDEX.md)

## Mit einem konkreten Projekt anfangen

| Öffentliches Projekt | Aufgabe | Praktischer Nutzen |
| --- | --- | --- |
| [Container Pulse](https://github.com/IMaugrenI/tof_container_pulse) | **Observe** | Lokale, schreibgeschützte Dashboards für Docker- und Host-Signale erzeugen. |
| [Local Knowledge](https://github.com/IMaugrenI/tof_local_knowledge) | **Ground** | Lokale Dokumente indexieren, Belege suchen und Fragen mit Quellenkontext beantworten. |
| [Local Builder](https://github.com/IMaugrenI/tof_local_builder) | **Generate** | Lokale Modelle mit kontrolliertem Quellzugriff und getrennter Ergebnisausgabe verwenden. |
| [Local Case Organizer](https://github.com/IMaugrenI/local_case_organizer) | **Structure** | Dateien in Register, Zeitachsen und prüfbare Exportpakete überführen. |

Jedes Projekt besitzt eigene Angaben zu unterstützten Plattformen, Funktionsumfang und Grenzen im README und unter `START_HERE.md`.

## Ein Ansatz, eigenständige Werkzeuge

**Observe → Ground → Generate → Structure** beschreibt ergänzende Verantwortlichkeiten. Es bedeutet **nicht**, dass bereits alle Repositories eine fertige gemeinsame Anwendung oder automatisch verbundene Verarbeitungskette bilden.

Die gemeinsame Entwicklungsrichtung ist praktisch: nach Möglichkeit lokal ausführen, vertrauenswürdige Quellen von generierten Ergebnissen trennen, Nachweise sichtbar halten und folgenreiche Aktionen nur mit passender Berechtigung zulassen.

## Architektur und Methoden

| Referenz | Zweck |
| --- | --- |
| [Architekturreferenz (V7)](https://github.com/IMaugrenI/tof-v7-public-frame) | Versionsbezogene öffentliche Beschreibung von Dienst- und Datengrenzen. V7 gehört zur Entwicklungsgeschichte; die interne Versionsfolge muss man nicht kennen. |
| [Modulideen](https://github.com/IMaugrenI/tof-module-ideas) | Größere Modulkandidaten vor einer Implementierung beschreiben und einordnen. |
| [Legacy Recovery Workbench](https://github.com/IMaugrenI/tof-legacy-recovery-workbench) | Ältere gemischte Materialien in Belege, Hypothesen und Prüfschritte trennen. |
| [Bridge Planning Method](https://github.com/IMaugrenI/tof-bridge-planning-method) | Vorbereitete Materialien zu prüfbaren Planungskandidaten weiterentwickeln, ohne sie stillschweigend zu ausführbarem Code zu erklären. |

Diese Repositories bilden **Methoden und Referenzen** ab; sie sind nicht mit den direkt nutzbaren Werkzeugen gleichzusetzen.

## Durch die Dokumentation navigieren

- [Einstieg](START_HERE_DE.md) — kurzer Lesepfad für neue Besucher.
- [Dokumentationsindex](docs/INDEX.md) — Überblick der öffentlichen Dokumentation.
- [Projektrollen](docs/01_product_line.md) — Aufgaben und mögliche Kombinationen.
- [Praktische Abläufe](docs/07_product_workflows.md) — öffentliche Beispiele mit beschriebenen Grenzen.
- [Projektkontext](docs/06_project-line.md) — Bezug zur umfassenderen privaten Entwicklungsarbeit.

## Was diese Arbeit zeigt

- Local-First-Architektur und selbst gehosteten Betrieb.
- Klare Zuständigkeiten für Eingabe, Wissen, Generierung und Ausgabe.
- Menschlich gesteuerte KI-Implementierung mit prüfbaren Ergebnissen.
- Unterscheidung zwischen Architekturzielen und nachweislich umgesetztem Verhalten.
- Öffentliche Beispiele ohne Offenlegung privater Betriebsumgebungen.

**Wichtig:** Eine öffentliche Architekturzeichnung ist kein Betriebsnachweis. Für Implementierung, Einrichtung, Plattformunterstützung und Entwicklungsreife ist jeweils das ausführbare Produkt-Repository maßgeblich. Eine pauschale Produktionsreife oder vollständige Integration der gesamten Projektfamilie wird nicht behauptet.

[Zurück zum GitHub-Profil von Jakob Kessler](https://github.com/IMaugrenI)
