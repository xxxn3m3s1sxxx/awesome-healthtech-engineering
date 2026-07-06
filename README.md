# Awesome HealthTech Engineering

Kuratierte Ressourcenliste für klinische Interoperabilität, Systemarchitektur und Software-Engineering im Gesundheitswesen.

## Standards & Spezifikationen

- [FHIR R4 (HL7)](https://hl7.org/fhir/R4/) — Aktueller REST-Standard für klinische Daten
- [DICOM PS3.x (NEMA)](https://www.dicomstandard.org/) — Bildgebungs-Standard (17 Teile)
- [HL7 v2](https://www.hl7.org/implement/standards/product_brief.cfm?product_id=185) — Legacy-Nachrichtenformat, weiterhin dominant im Klinik-Alltag
- [IHE Integration Profiles](https://www.ihe.net/resources/technical_frameworks/) — Profile für geräteübergreifende Workflows
- [SNOMED CT](https://www.snomed.org/) — Klinische Terminologie
- [LOINC](https://loinc.org/) — Labordaten-Codierung
- [ICD-11 (WHO)](https://icd.who.int/) — Diagnoseklassifikation
- [GS1 Healthcare GTIN](https://www.gs1.org/healthcare) — Medizinprodukte-Identifikation

## Open Source Tooling

### DICOM

- [dcm4chee](https://github.com/dcm4che/dcm4chee-arc-light) — Enterprise PACS Archive (Java, J2EE)
- [Orthanc](https://www.orthanc-server.com/) — Leichtgewichtiger DICOM-Server (C++, REST-API)
- [pydicom](https://github.com/pydicom/pydicom) — Pure-Python DICOM-Bibliothek
- [fo-dicom](https://github.com/fo-dicom/fo-dicom) — .NET DICOM-Bibliothek
- [DCMTK](https://dicom.offis.de/dcmtk.php.en) — C++ DICOM-Toolkit (Referenzimplementierung)

### FHIR

- [HAPI FHIR](https://hapifhir.io/) — Java FHIR Server + Client (Referenz)
- [FHIR .NET API](https://github.com/FirelyTeam/firely-net-sdk) — .NET SDK (Firely)
- [fhirpath.js](https://github.com/HL7/fhirpath.js) — FHIRPath für JavaScript
- [FHIR Validator](https://github.com/hapifhir/org.hl7.fhir.core) — Offizieller FHIR R4 Validator
- [SUSHI](https://github.com/FHIR/sushi) — FHIR Shorthand → StructureDefinition Compiler

### Interoperabilitäts-Engines

- [Mirth Connect](https://github.com/nextgenhealthcare/connect) — HL7 v2/v3 + FHIR Integration Engine (Java)
- [Apache Camel](https://camel.apache.org/components/next/fhir-component.html) — FHIR-Komponente für Routing
- [OpenHIM](https://openhim.org/) — Open Source Health Information Mediator

### Testdaten

- [Imaging Data Commons (IDC)](https://imaging.datacommons.cancer.gov/) — 50M+ anonymisierte DICOM-Studien (NCI)
- [MIMIC-CXR](https://physionet.org/content/mimic-cxr/2.0.0/) — 377k Röntgenbilder (MIT)
- [Synthea](https://github.com/synthetichealth/synthea) — Synthetische FHIR-Patientendaten
- [FHIR Sample Data (Microsoft)](https://github.com/microsoft/fhir-server-samples) — Beispiel-Ressourcen für Dev/Test
- [RSNA DICOM Sample Images](https://www.rsna.org/education/ai-resources-and-training/ai-image-challenge) — Radiologische Beispieldatensätze

## Resilience & System-Architektur

- [Resilience4j](https://resilience4j.readme.io/) — Circuit Breaker + Retry für Java (Vorbild für Nicht-Java-Implementierungen)
- [dicom-fhir-resilient-bridge](https://github.com/xxxn3m3s1sxxx/dicom-fhir-resilient-bridge) — Production-Grade Architektur-Scaffold mit Circuit Breaker, DLQ und FHIR-R4-Generierung
- [Cloud Design Patterns (Azure)](https://learn.microsoft.com/en-us/azure/architecture/patterns/) — Circuit Breaker, Retry, Queue-Based Load Leveling
- [Stoplight Spectral](https://github.com/stoplightio/spectral) — API Style-Guide Linter für FHIR-REST-konforme APIs

## Regulierung & Compliance

- [Medizinprodukteverordnung (MDR) 2017/745](https://eur-lex.europa.eu/eli/reg/2017/745/oj) — EU-Regulierung für medizinische Software
- [IEC 62304](https://www.iso.org/standard/75485.html) — Software-Lebenszyklus für Medizinprodukte
- [HIPAA Security Rule (45 CFR 164)](https://www.hhs.gov/hipaa/for-professionals/security/index.html) — USA: Sicherheitsanforderungen für Patientendaten
- [DSGVO / GDPR Art. 17](https://gdpr-info.eu/art-17-gdpr/) — Recht auf Löschung ("Right to Erasure")
- [BfArM DiGA-Leitfaden](https://www.bfarm.de/DE/Medizinprodukte/Aufgaben/DiGA/_node.html) — Digitale Gesundheitsanwendungen (Deutschland)
- [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) — Security Controls für Informationssysteme

## Community & Austausch

- [FHIR Zulip Chat](https://chat.fhir.org/) — Offizieller HL7-Diskussionskanal (aktivste Community)
- [HL7 Europe](https://www.hl7europe.org/) — Interoperabilitäts-Standardisierung in Europa
- [DICOM Newsgroup](https://groups.google.com/g/comp.protocols.dicom) — Mailingliste (USENET-Ära, aber aktiv)
- [Open Health Informatics](https://discourse.ohie.org/) — Diskussionsforum der OpenHIE-Community
- [/r/healthIT (Reddit)](https://www.reddit.com/r/healthIT/) — HealthIT-Community
- [IHE International Connectathon](https://www.ihe.net/participate/connectathon/) — Jährliches Interoperabilitäts-Test-Event

## Learning Resources

- [FHIR Foundations (HL7)](https://hl7.org/fhir/R4/foundation.html) — Offizielles FHIR-Tutorial
- [DICOM PS3.5 Data Structures](https://dicom.nema.org/medical/dicom/current/output/chtml/part05/PS3.5.html) — DICOM-Datenmodell
- [Coursera: HI-FIVE (Health Informatics)](https://www.coursera.org/specializations/health-informatics) — Einführung in die Medizininformatik (Columbia University)
- [MIT Critical Data Book](https://criticaldata.mit.edu/book/) — Open-Access-Buch zu Data Science im Gesundheitswesen
- [OHDSI Tutorials](https://www.ohdsi.org/) — Observational Health Data Sciences and Informatics

## Lizenz

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
