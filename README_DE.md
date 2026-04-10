# ToF Showcase

> Die englische Hauptfassung liegt in `README.md`.

Öffentlicher Architektur-Einstieg für die breitere ToF / Veth-Projektlinie.

Ich nutze dieses Repo, um die Struktur öffentlich zu erklären, ohne private Runtime-Details offenzulegen.
Es ist der beste Ort, um zu verstehen, wie die sichtbare Repo-Familie zusammenhängt.

Dieses Repository ist ein öffentlicher Beleg für Architektur- und Leseregel-Arbeit unter KI-gestützten Build-Bedingungen. Es soll kein klassischer Beweis für manuell Zeile für Zeile geschriebenen Code sein. Es soll zeigen, wie öffentliches Systemframing, Trennlogik und kontrollierte Erklärung unter menschlicher Führung geformt werden können.

Lies dieses Repo, wenn du die Architektursicht des Projekts sehen willst und nicht die Sicht auf das lauffähige Produkt.

## Einstieg

- [`docs/01_overview.md`](docs/01_overview.md) — kompakter Überblick
- [`docs/02_what-is-tof.md`](docs/02_what-is-tof.md) — was ToF ist und was nicht
- [`docs/03_layer-separation.md`](docs/03_layer-separation.md) — Trennung von Räumen und Ebenen
- [`docs/05_public-chain.md`](docs/05_public-chain.md) — reduzierte öffentliche Kettenlesart
- [`docs/06_project-line.md`](docs/06_project-line.md) — wie die öffentliche Repo-Familie zusammenhängt

## Scale

Der hier gezeigte öffentliche Rahmen steht vor einem privaten Produktivsystem, das alleine aufgebaut und betrieben wird — 52 containerisierte Services auf einem self-hosted Linux-Server, aktiv seit Anfang 2025. Was hier öffentlich gezeigt wird, ist bewusst reduziert. Das darunterliegende System ist es nicht.

## Meine Rolle in diesem Repo

Meine Rolle hier ist vor allem:

1. Architektur und Trennlogik
2. öffentliche Rahmung und Leseregeln
3. Scope-Reduktion und Review
4. KI-gestützte Umsetzung unter meiner Führung

## Was dieses Repo zeigt

1. ToF als technische Struktur, Kettenlogik, Governance, Safety, Runtime-, State- und Archiv-Denke
2. Veth als eigene Identitäts-, Spiegel- und Ausdrucksschicht
3. warum öffentliche Erklärung von privater Runtime-Wahrheit getrennt bleiben muss
4. wie Grenzen und Leseregeln den öffentlichen Rahmen ehrlich halten

## Warum dieses Repo existiert

1. um einen nachvollziehbaren öffentlichen Einstieg in die breitere Projektlinie zu geben
2. um zu verhindern, dass das Projekt nur als Bot-Oberfläche gelesen wird
3. um Architekturdenken, Trennlogik und Dokumentationsdisziplin sichtbar zu machen
4. um öffentliche und private Ebenen klar getrennt zu halten

## Was dieses Repo nicht ist

1. nicht der private Produktionsstand
2. nicht der vollständige Runtime-Code
3. nicht das vollständige Compose- oder Infrastruktur-Setup
4. kein versteckter interner Dump

## Für Arbeitgeber

Dieses Repo ist nützlich, wenn du sehen willst, wie ich über Folgendes denke:

1. Systemgrenzen
2. geschichtete Architektur
3. public-safe Dokumentation
4. die Trennung von Erklärung und Implementierungswahrheit

## Verwandte öffentliche Repos

- [`tof_local_builder`](https://github.com/IMaugrenI/tof_local_builder) — lauffähiger lokaler Builder-Stack
- [`tof_local_knowledge`](https://github.com/IMaugrenI/tof_local_knowledge) — on-prem lokales Wissenssystem
- [`tof_v7_public_frame`](https://github.com/IMaugrenI/tof-v7-public-frame) — reduzierter öffentlicher Rahmen für V7-Grenzen
