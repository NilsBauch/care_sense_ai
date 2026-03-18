# CareSens AI

## Überblick
CareSens AI ist eine datengetriebene Plattform zur Analyse von Verhaltensmustern älterer Menschen, die selbstständig zu Hause leben.  
Das System kombiniert IoT-Sensordaten und Wearable-Informationen, um Auffälligkeiten im Alltag frühzeitig zu erkennen.

## Zielsetzung
Ziel des Projekts ist die Entwicklung eines Edge-basierten KI-Systems, das:
- Sensordaten in Echtzeit erfasst und verarbeitet
- individuelle Tagesabläufe lernt
- Abweichungen im Verhalten erkennt
- bei kritischen Situationen Warnungen auslöst

## Hauptfunktionen
- Aktivitätsüberwachung mittels IoT-Sensoren (z. B. Bewegung, Präsenz)
- Integration von Gesundheitsdaten aus Wearables (z. B. Herzfrequenz, Schritte)
- Speicherung und Verarbeitung von Zeitreihendaten
- KI-basierte Anomalieerkennung
- Ressourcenschonender Betrieb auf einem Raspberry Pi

## Architektur (High-Level)
Sensoren & Wearables → MQTT → Datenverarbeitung → Datenbank → KI-Analyse → Dashboard & Alerts

## Motivation
Das Projekt unterstützt ein selbstbestimmtes Leben im Alter, indem potenzielle Risiken frühzeitig erkannt werden.  
Gleichzeitig wird durch lokale Datenverarbeitung besonderer Wert auf Datenschutz gelegt.

## Technologie-Stack
- Docker / Docker Compose
- MQTT (Mosquitto)
- InfluxDB (Zeitreihendatenbank)
- Python (Datenverarbeitung & KI)
- Streamlit (Visualisierung)

## Status
In Entwicklung 🚧
