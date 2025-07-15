# Green Coding im Überblick

- Programmierpraxis, die darauf ausgelegt ist, möglichst umweltverträgliche Softwaresysteme zu erstellen
- Setzt auf allen Ebenen der Softwareentwicklung an
    - Architektur der Software
    - Zugrundeliegender Entwicklungsansatz
    - Verworrener + wenig optimierter Code soll in grünen Programmen vermieden werden -> Grund: Unzureichend optimierter Code führt häufig Anweisungen aus, die für Programmlogik nicht zwingend erforderlich ist -> unnötiger Zugriff auf Ressourcen => Energieverschwendung

Säulen
des Green Coding

- Grüne Architektur
    - Grundlegender Aufbau der zu programmierenden Anwendung
    - Optimierung hinsichtlich Energieverbrauch
    - Code so bündeln, dass jederzeit optimale Auslastung der Hardware gewährleistet + so weniger Strom benötigt wird
    - Automatische Abschaltmechanismen bei Nichtgebrauch von Software
- Grüne Logik
    - Programmcode optimieren, dass Anwendung von Programmen nicht durch unnötige Codeanweisungen entschleunigt wird
    - Wahl von Ressourcenschonenden Dateiformaten
    - Effiziente Datenstrukturen
- Grüne Methodik
    - Softwareentwicklungsprozess
    - Agile Softwareentwicklungsmodelle
    - Kleinschrittiges Entwickeln + Testen soft dafür dass Programmbestandteile mit schlechter Energieeffizienz früh erkannt + verändert werden können
- Grüne Plattform
    - Hardware
    - Auslastung von Servern
    - Server, die unter geringer Last laufen, brauchen mehr Strom als nötig
    - Cloud Computing als Abhilfe -> Ressourcen flexibel skalieren + an individuellen Bedarf anpassen
    - Energiebedarf des Anbieters mit erneuerbaren Energien decken

Effizienzvergleich
von Programmiersprachen

- Energieeffizienteste Programmiersprache: C, auch C++
    - Hardwarenahe Programmiersprache, geringe Abstraktionsebene
    - Hardwareressourcen können effizient genutzt werden
    - Direkte Speicherverwaltung
- Rust
    - Kontrollierte Speicherverwaltung -> effiziente Speicherverwaltung
    - Hohes Maß an Parallelisierung -> Hardwareressourcen werden optimal ausgelastet
- Python
    - Sehr beliebt
    - Schlecht in Energieeffizienz
    - Programme werden erst zur Laufzeit interpretiert, nicht kompiliert
    - Dynamische Typisierung der Sprache
- Ähnliche Gründe auch Javascript