# Forschungsdaten in den Repositorien von FU Berlin, HU Berlin und TU Berlin.
## Ansätze zur Analyse von Metadaten

Dieses GitHub-Repositorium beinhaltet Daten, die Forschungsdatensätze in den Repositorien von FU Berlin, HU Berlin und TU Berlin beschreiben.
Die Daten wurden am 20.02.2024 erhoben.

### Methode
Zunächst wurden DOIs von Forschungsdatensätzen ermittelt, die über den Zeitraum von 2010-01-01T00:00:00Z bis 2023-12-31T23:59:59Z über die drei Repositorien Refubium (FU Berlin / Charité), edoc-Server (HU Berlin) und DepositOnce (FU Berlin) veröffentlicht wurden. Die DOIs wurden über die OAI-PMH-Schnittstelle der Repositorien bezogen. Eingeschränkt wurde die Abfrage auf die OAI-PMH-Sets, die Forschungsdaten beinhalten:

- [Refubium](https://refubium.fu-berlin.de/oai): doc-type:ResearchData (n = 96)
- [edoc-Server](https://edoc.hu-berlin.de/oai): researchData (n = 76)
- [DepositOnce](https://api-depositonce.tu-berlin.de/server/oai): col_11303_13955 (n = 375)

Anschließend wurden Metadaten, die mit diesen DOIs verknüpft wurden, im Format Dublin Core abgefragt. Die Bewertung der Erfüllung der FAIR Data Principles erfolgte über F-UJI.

### Ordnerstruktur
- **DOIs**: DOIs der Forschungsdatensätze
- **F-UJI**: Ergebnisse der Evaluation mit F-UJI
- **OAI-PMH**: Metadaten im Format Dublin Core
