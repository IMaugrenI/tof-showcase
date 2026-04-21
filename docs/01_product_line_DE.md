# Öffentliche Produktlinie

Dieses Repository ist Teil einer modularen, lokalen Produktlinie.

Jedes Tool funktioniert für sich allein.
Einige Tools können in definierten Kombinationen zusammen genutzt werden.
Nicht alle Kombinationen sind vorgesehen.

> Diese Seite beschreibt Rollen und Kombinationen. Für die Einordnung in die Gesamtprojektlinie siehe `06_project-line_DE.md`.

## Rollen

| Rolle | Repo |
|------|------|
| Beobachten | tof_container_pulse |
| Struktur | local_case_organizer |
| Erzeugen | tof_local_builder |
| Grundlage / Wissen | tof_local_knowledge |

## Standalone

Jedes Tool ist eigenständig nutzbar.

## Empfohlene Kombinationen

- Knowledge + Builder
- Builder + Organizer
- Knowledge + Organizer

## Kette

Knowledge → Builder → Organizer

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
