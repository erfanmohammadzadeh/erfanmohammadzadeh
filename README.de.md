# Erfan Mohammadzadeh

**Software Engineer · 3D-Rekonstruktion und Analysealgorithmen**

[erfanmohammadzadeh.en@gmail.com](mailto:erfanmohammadzadeh.en@gmail.com) · [LinkedIn](https://www.linkedin.com/in/erfan-mohammadzade-076791178) · [GitHub](https://github.com/erfanmohammadzadeh)

[English](README.md) · **Deutsch**

## Profil

Software Engineer mit Schwerpunkt auf 3D-Rekonstruktion und den zugehörigen Analysealgorithmen. Ich überführe räumliche Rohmessungen — LiDAR-Punktwolken, Kamerabilder und Gebäudegrundrisse — in strukturierte Geometrie: Filterung, Segmentierung, Oberflächenrekonstruktion, geometrische Regularisierung und quantitative Prüfung des Ergebnisses.

Aktuelle Arbeit ist City4CFD / QCity4CFD: LoD-Stadtnetze für CFD aus Punktwolken und Grundrissen, umgesetzt mit PCL, PDAL, CGAL, VTK und Open3D. Dieselbe algorithmische Arbeit gilt für Kamerageometrie (Kalibrierung, Intrinsik, Verzeichnung) und für Signalstrecken, in denen eine Messung gefiltert, klassifiziert und geprüft wird, bevor sie als verlässlich gilt.

Desktop-Werkzeuge für diese Strecken entstehen in C++ / Qt. Parallel dazu lerne ich fortgeschrittene Technologie und Architektur in C# und .NET, damit Rekonstruktionsergebnisse hinter einem wartbaren Dienst und einer Datenbank liegen können.

## Ausrichtung

- **3D-Rekonstruktion:** Punktwolken und Grundrisse zu LoD-Stadtnetzen, Oberflächenrekonstruktion, Netzregularisierung und simulationsfertige Geometrie.
- **Analysealgorithmen:** Filterung, Segmentierung, Merkmalsextraktion, geometrische Anpassung und Genauigkeitsprüfung gegen eine bekannte Referenz.
- **Im Aufbau:** fortgeschrittene Technologie und Architektur in C# und .NET — ASP.NET Core, Anwendungsstruktur und APIs auf relationalen Daten.

## Kenntnisse

| Bereich | Inhalt |
| --- | --- |
| 3D-Rekonstruktion | PCL, CGAL, VTK, Open3D, City4CFD / LoD-Modellierung |
| Analysealgorithmen | Filterung, Segmentierung, Oberflächenrekonstruktion, geometrische Regularisierung, Netzprüfung |
| Geodaten | PDAL, GDAL, QGIS, ArcGIS |
| Bildverarbeitung und Kamerageometrie | OpenCV, Kalibrierung, Intrinsik und Extrinsik, Verzeichnung |
| Sprachen | C++, Python, C#, SQL, QML |
| Desktop | Qt (Widgets / QML), plattformübergreifende Builds |
| Daten | SQL, SQLite, XML, strukturierte Verarbeitungspipelines |
| .NET und C# (im Aufbau) | Fortgeschrittene Plattformtechnologie und Architektur, ASP.NET Core, Web API, REST |
| Systeme | Linux (LPIC-1) |

## Berufserfahrung

### Geospatial Data Engineer — Image Horizon (Data Horizon)

Teheran, Iran · November 2025 – heute · parallel zu Amvaj Negar

- Verantwortlich für den Rekonstruktionspfad City4CFD / QCity4CFD: Punktwolken und Gebäudegrundrisse zu Stadtnetzen in LoD 3.0, 2.2, 2.0, 1.3 und 1.0 für CFD, mehr als 20.000 Gebäude.
- Verarbeitungsstufen mit PCL, PDAL, GDAL, CGAL und VTK: Filterung, Segmentierung, Oberflächenrekonstruktion, geometrische Regularisierung, Rendering und Qualitätssicherung der Netze.
- Über 90 % Rekonstruktionsgenauigkeit in der hochdetaillierten Gebäudepipeline (Python, NumPy, Open3D, PDAL sowie GIS in QGIS / ArcGIS).
- Verbindung zwischen GIS-Betrieb und Simulationsteams durch prüfbare, simulationsfertige Geometrie.

### Senior Software Engineer — Amvaj Negar Sepahan Co.

Isfahan, Iran · April 2024 – heute

- Entwurf und Pflege der Holter-EKG-Desktopsoftware (C++ / Qt Widgets): Langzeit-EKG-Import, Detektion von P-Q-R-S-T, Klassifikation von Schlagvorlagen, Arrhythmie-Unterstützung, SQLite-Persistenz sowie XML- und PDF-Berichte.
- QCardio als Validierungsumgebung für EKG-Bibliotheken: MIT-BIH Arrhythmia als strukturierter Testsatz, Prüfung gegen ärztlich annotierte Referenzdaten.
- Verantwortung für die Korrektheit der Signalverarbeitung: Filterung, Merkmalsextraktion, Klassifikation und Regressionstests, auf die Klinik und Entwicklung sich gemeinsam stützen können.

### Software Engineer — Data Image Rayan Co.

Isfahan, Iran · Juni 2024 – März 2025 · parallel zu Amvaj Negar

- ANPR-Überwachung für die Parkzufahrt: Live-Kameras, Fahrzeugerkennung, Kennzeichenausschnitt, OCR-Prüfung und Schrankensteuerung.
- Weniger manuelle Eingriffe an der Schranke durch eine Echtzeit-Bildstrecke vom Einzelbild bis zur Zugangsentscheidung.

### Junior Software Engineer — Tivan Sanat (Dade Pardazan Tivan Sanat)

Isfahan, Iran · April 2021 – Dezember 2022

- Plattformübergreifendes Kamerakalibrierungs-Werkzeug in C++/Qt und OpenCV: Erkennung von Schachbrett und Kalibrierziel, Keypoints, Intrinsik und Extrinsik, radiale und tangentiale Verzeichnung, Brennweite, Hauptpunkt, Sichtfeld und Korrekturmatrizen.
- Export der Kalibrierergebnisse (SQLite, XML, PDF) für die optische Qualitätssicherung in der Produktion.

## Ausgewählte Projekte

**ASP.NET Core Web API (CRUD)** — Lernen fortgeschrittener C#- und .NET-Architektur  
REST-Endpunkte für Anlegen, Lesen, Aktualisieren und Löschen gegen eine SQL-Datenbank: Request-Verarbeitung, Datenzugriff und Dienststruktur.  
`C#` `ASP.NET Core` `Web API` `SQL`

**QCity4CFD** — Data Horizon · Januar 2025  
LoD-2.2-Rekonstruktion aus LiDAR und Gebäudegrundrissen, mit Netzregularisierung und CFD-orientierten Stadtmodellen.  
`Python` `Open3D` `PDAL` `CGAL` `QGIS` `ArcGIS` `City4CFD`

**QCardio** — Amvaj Negar Sepahan · Juni 2026  
Validierung von EKG-Bibliotheken gegen annotierte MIT-BIH-Aufnahmen, mit automatischer Bewertung klinischer Signalformen.

**EKG-Holter-Software** — Amvaj Negar Sepahan · April 2024  
Desktop-Holter-Analyse: Wellendetektion, Vorlagen, Arrhythmie-Markierungen und Berichte.

**Prüfstand für Parameter einer Sichtkamera** — Tivan Sanat · Dezember 2022  
Produktionskalibrierung praktischer Kameraparameter für genaue Darstellung und Messtechnik.

## Ausbildung

**B.Sc. Elektrotechnik — Nachrichtentechnik**  
Semnan University, Semnan, Iran · Oktober 2019 – Januar 2024 · GPA 3,2 / 4,0

Studium und Praxis in Signalverarbeitung, Nachrichtentechnik und Regelungstechnik. Angewandte Signalverarbeitung (Filterung, Merkmale, Echtzeit-Klassifikation) in späteren Industriesystemen.

## Zertifikat

**Foundations of Coding: Full-Stack** — Microsoft / Coursera · Oktober 2025  
[Nachweis prüfen](https://www.coursera.org/account/accomplishments/verify/XIAL95E2ZNBP)

## Sprachen

- Persisch (Farsi): Muttersprache
- Englisch: beruflich sicher in Lesen, Schreiben, Sprechen und Hören; eingesetzt für technische Dokumentation, Code und Kommunikation mit Auftraggebern
- Deutsch: beruflich sicher in Lesen, Schreiben, Sprechen und Hören; eingesetzt für technische Dokumentation, Code und Kommunikation mit Auftraggebern
