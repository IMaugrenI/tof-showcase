# Öffentliche Dokumentation und Grenzen des privaten Systems

**ToF Systems veröffentlicht sowohl nutzbare Werkzeuge als auch Architekturreferenzen.** Beides ist zu unterscheiden: Öffentlicher Code kann direkt geprüft werden; das Verhalten einer privaten Runtime ist dagegen nicht durch ein öffentliches Architekturpapier nachgewiesen.

## Was dieses Showcase zeigen darf

- Architektur- und Zuständigkeitsmodelle auf hoher Ebene.
- Öffentliche technische Prinzipien und reduzierte Verarbeitungsbeispiele.
- Links zu Quellcode, Demos und Prüfungen **in den getrennten öffentlichen Produkt-Repositories**.
- Historische Begriffe, wo sie zum Verständnis von Architekturentscheidungen wichtig sind.
- Umfang und Grenzen der öffentlichen Projektfamilie.

## Was außerhalb dieses Showcase bleibt

- Vollständiger Quellcode des privaten Systems und Produktivinfrastruktur.
- Sensible Compose-/Runtime-Konfiguration, Host-Pfade und Netzwerkdetails.
- Zugangsdaten, private Kennungen, Secrets, Rohlogs und personenbezogene Daten.
- Private Sicherheitskontrollen, Betreiberdetails und nicht freigegebene interne Nachweise.

## Leseregel

**Architekturabsicht ist kein Betriebsnachweis.** Ein öffentliches Beispiel sollte klar benennen, ob es ein Konzept erläutert, ein funktionierendes öffentliches Werkzeug zeigt oder durch eine konkrete Runtime-Prüfung belegt ist. Das jeweilige Repository bleibt maßgeblich für echte Funktionen und Abhängigkeiten.

Ziel ist eine verständliche, brauchbare öffentliche Darstellung — weder unnötige Geheimniskrämerei noch die Offenlegung sensibler privater Betriebsabläufe.

[Projektfamilie](../README_DE.md)
