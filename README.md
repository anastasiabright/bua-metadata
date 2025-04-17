# Forschungsdaten in den Repositorien von FU Berlin, HU Berlin und TU Berlin.
## Ansätze zur Analyse von Metadaten

Dieses GitHub-Repositorium beinhaltet Daten, die Forschungsdatensätze in den Repositorien von FU Berlin, HU Berlin und TU Berlin beschreiben.
Die Daten wurden am 03.03.2025 erhoben.

### Methode
Zunächst wurden DOIs von Forschungsdatensätzen ermittelt, die über den Zeitraum von 2010-01-01T00:00:00Z bis 2024-12-31T23:59:59Z über die drei Repositorien Refubium (FU Berlin / Charité), edoc-Server (HU Berlin) und DepositOnce (FU Berlin) veröffentlicht wurden. Die DOIs wurden über die OAI-PMH-Schnittstelle der Repositorien bezogen. Eingeschränkt wurde die Abfrage auf die OAI-PMH-Sets, die Forschungsdaten beinhalten:

- [Refubium](https://refubium.fu-berlin.de/oai): doc-type:ResearchData (n = 78)
- [edoc-Server](https://edoc.hu-berlin.de/oai): researchData (n = 31)
- [DepositOnce](https://api-depositonce.tu-berlin.de/server/oai): col_11303_13955 (n = 378)

Anschließend wurden Metadaten, die mit diesen DOIs verknüpft wurden, im Format DIM ([DSpace Intermediate Metadata](https://wiki.lyrasis.org/plugins/viewsource/viewpagesrc.action?pageId=22021312)) abgefragt. Die Bewertung der Erfüllung der FAIR Data Principles erfolgte über F-UJI.

### Ordnerstruktur
- **DOIs**: DOIs der Forschungsdatensätze
- **F-UJI**: Ergebnisse der Evaluation mit F-UJI
- **OAI-PMH**: Metadaten im Format DIM
