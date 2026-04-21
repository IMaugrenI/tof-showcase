# Produkt-Workflows

Diese Seite zeigt, wie die öffentlichen Produkt-Repositories praktisch zusammen genutzt werden können.

Diese Workflows sind bewusst manuell und explizit.

## Grundprinzip

Jedes Tool funktioniert alleine.
Kombination ist optional.

## Workflow 1 — Knowledge + Builder

### Use Case

Du willst evidenzbasierte Grundlage vor der Generierung.

### Start

Starte in `tof_local_knowledge`.

### Übergabe

1. Dokumente durchsuchen
2. relevante Evidenz finden
3. diese gezielt in den Builder übernehmen
4. im `tof_local_builder` als kontrollierten Input nutzen

### Ergebnis

Die Generierung bleibt an realer Evidenz gebunden.

### Nicht tun

- keine generierten Inhalte als Wahrheit zurückführen

## Workflow 2 — Builder + Organizer

### Use Case

Du willst generierte Inhalte sauber strukturieren.

### Start

Starte im Builder.

### Übergabe

1. Output erzeugen
2. prüfen
3. relevante Inhalte in den Organizer übernehmen
4. dort strukturieren

### Ergebnis

Aus Output wird ein strukturiertes Dossier.

## Workflow 3 — Knowledge + Organizer

### Use Case

Du willst Evidenz direkt strukturieren.

### Übergabe

Knowledge → Organizer

### Ergebnis

Weniger manuelle Sortierung.

## Workflow 4 — Full Chain

Knowledge → Builder → Organizer

### Ergebnis

Evidenz → Generierung → Struktur

## Pulse

`tof_container_pulse` bleibt Beobachtung.

## Grenzen

- keine Rückkopplung
- keine Automatik
- keine Vollvernetzung
