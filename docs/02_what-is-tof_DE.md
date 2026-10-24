# Technische Architektur — Was ToF bedeutet

**ToF** bezeichnet den technischen Strukturierungsansatz innerhalb der übergreifenden Arbeit an **ToF Systems**. Es steht nicht einfach für einen Discord-Bot, eine Chat-Oberfläche oder ein Sprachmodell.

Die Grundidee ist eine modulare Architektur mit klarer Behandlung von Verarbeitung, Berechtigung, Schutz, Zustand und historischen Aufzeichnungen.

## Technische Schwerpunkte

- Eindeutige Verarbeitungsschritte und Zuständigkeiten.
- Grenzen zwischen Diensten und Datenräumen.
- Governance und Schutz vor folgenreichen Aktionen.
- Trennung von aktuellem Zustand, gespeicherter Historie und geregeltem Referenzmaterial.
- Plattformunabhängige Kernlogik mit Adaptern an den Schnittstellen.

Das beschreibt **Architekturprinzipien** und behauptet nicht, dass jedes Detail in jedem öffentlichen Repository umgesetzt ist.

## Was der Name nicht bedeutet

Der technische Ansatz ist nicht auf einen Chatbot, LLM-Wrapper, monolithischen Bot oder eine bestimmte Plattform beschränkt. Die öffentlichen Werkzeuge sind eigenständig nutzbar und erfordern keine private Assistenten-Runtime.

## Historische Bezeichnungen: ToF und V’eth

Frühere Architekturdokumente unterscheiden **ToF (technische Struktur)** und **V’eth (Identität und Ausdruck)**. Diese Trennung verhindert, dass eine Persona oder symbolische Darstellung unbemerkt Systementscheidungen bestimmt.

Für die heutige öffentliche Orientierung ist **ToF Systems** die gemeinsame Projektidentität. Die beiden älteren Begriffe bleiben hier nur dort erhalten, wo sie eine wichtige Architekturgrenze erläutern.

[Weiter zur Zuständigkeitstrennung](03_layer-separation_DE.md)
