# Architekturgrenzen — Zuständigkeiten und Datenräume

Ein zentrales Prinzip der früheren ToF-Architektur ist, dass unterschiedliche Verantwortlichkeiten nicht stillschweigend ineinander übergehen dürfen.

## Bereiche und Zuständigkeiten

| Bereich | Aufgabe | Wichtige Grenze |
| --- | --- | --- |
| Technischer Kern (ToF) | Verarbeitung und Betriebsstruktur | Nicht durch Stil oder Persona gesteuert |
| Identität und Ausdruck (historisch V’eth) | Darstellung und Kommunikation des Assistenten | Keine versteckte Berechtigung, Systemzustände zu ändern |
| Runtime | Tatsächlich aktive Dienste und Betriebszustand | Nicht mit Planung oder Dokumentation gleichzusetzen |
| Werkbank | Älteres Material untersuchen, trennen und vorbereiten | Keine automatische Freigabe in die Runtime |
| Archiv | Gespeicherte Historie und Herkunft | Nicht automatisch aktueller Wahrheitsstand |
| Kanon | Geregeltes Referenzmaterial | Nicht identisch mit dem laufenden Runtime-Zustand |

Das sind **konzeptionelle Grenzen** der öffentlichen Architekturreferenz. Ihre Beschreibung ist kein Nachweis, dass jede Umsetzung bereits betrieben wird.

## Warum die Trennung wichtig ist

Archiviertes darf nicht unbemerkt zum aktuellen Zustand werden. Planungskandidaten dürfen nicht automatisch ausführbare Änderungen auslösen. Ausdruck und Identität verleihen sich keine eigene Berechtigung. Technische Entscheidungen brauchen klar ausgewiesene Quellen, Autorität und Prüfung.

## Öffentlicher Umfang

Das Repository erklärt diese Beziehungen, ohne private Pfade, Zugangsdaten, interne Betreiberdetails oder vollständige Runtime-Mechanismen zu veröffentlichen.

[Öffentliches Verarbeitungsmodell](05_public-chain_DE.md) · [Referenz- und Identitätsgrenzen](08_canon-boundary_DE.md)
