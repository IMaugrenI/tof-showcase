# Öffentliche Werkzeuge — Rollen und manuelle Kombinationen

Die öffentlichen Werkzeuge von ToF Systems sind eigenständige Local-First-Projekte mit ergänzenden Aufgaben.

Jedes Tool funktioniert für sich allein.
Einige Tools können in definierten Kombinationen zusammen genutzt werden.
Nicht alle Kombinationen sind vorgesehen.

> Diese Seite beschreibt Rollen und Kombinationen. Für die Einordnung in die Gesamtprojektlinie siehe `06_project-line_DE.md`.

## Rollen

| Rolle | Repo |
|------|------|
| Beobachten | tof_container_pulse |
| Grundlage / Wissen | tof_local_knowledge |
| Erzeugen | tof_local_builder |
| Struktur | local_case_organizer |

## Standalone

Jedes Tool ist eigenständig nutzbar.

## Empfohlene Kombinationen

- Knowledge + Builder
- Builder + Organizer
- Knowledge + Organizer

## Optionale manuelle Abfolge

Knowledge → Builder → Organizer

Das ist ein **bewusst vom Nutzer gesteuertes Übergabebeispiel**, keine bereits veröffentlichte gemeinsame Runtime und kein automatisierter Ablauf. Material muss an jedem Übergang geprüft werden.

## Sonderrolle

`tof_container_pulse` ist rein beobachtend.

## Nicht vorgesehen

- Organizer → Builder (automatisch)
- Builder → Knowledge (Rückkopplung)
- Pulse steuert andere Tools
- vollständige Vermischung aller Tools

## Prinzipien

- Tools bleiben eigenständig
- keine gemeinsame Runtime
- keine versteckten Integrationen
- Nutzer entscheidet bewusst über Kombinationen
