# Technische Leitplanken — Geltungsbereich und Einordnung

Die folgenden Punkte sind **öffentlich beschreibbare Entwurfsentscheidungen aus der früheren ToF-Systemarchitektur**:

- Docker-first-Ausrichtung des Betriebs
- Postgres-only-Datenbankausrichtung innerhalb dieser Architektur
- ausdrücklich definierte Dienst- und Zuständigkeitsgrenzen
- Fail-closed-Verhalten statt stiller Umgehungen
- Audit- und Herkunftsnachweise als Entwurfsprinzip
- Append-only-orientierte Nachvollziehbarkeit, wo sinnvoll
- plattformneutraler Kern mit externen Adaptern
- Sprachmodell-Ausgabe spät im Verarbeitungsmodell, nicht als Autoritätsquelle
- Datenschutz und Einwilligung als übergreifende Aufgaben

## Der Geltungsbereich ist wichtig

Diese Vorgaben gehören zur **beschriebenen Architektur**, nicht automatisch zu jedem eigenständigen öffentlichen Produkt. Ein schreibgeschützter Generator statischer Statusseiten kann beispielsweise ohne Postgres sinnvoll sein; die tatsächlichen Abhängigkeiten stehen im README des jeweiligen Werkzeugs.

Begriffe wie *Fail-closed*, *Audit-first* oder *Postgres-only* beschreiben **angestrebte Architekturentscheidungen** und sind keine unabhängig verifizierte Garantie für die vollständige private Runtime.

## Wo Nachweise zu finden sind

Für tatsächlich vorhandenes Verhalten, Abhängigkeiten und unterstützte Plattformen sind das [Produkt-Repository](../README_DE.md), dessen Schnellstart, Prüfungen und dokumentierte Grenzen maßgeblich. Private Sicherheitsdetails werden hier bewusst nicht veröffentlicht.
