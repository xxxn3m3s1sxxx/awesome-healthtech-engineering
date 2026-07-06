# Coffee-Chat Outreach Drafts

## FHIR Zulip — "interoperability" stream

**Subject:** DICOM → FHIR bridge with circuit-breaker resilience

Hey everyone,

I just open-sourced a project I've been working on — a production-oriented DICOM-to-FHIR bridge with:
- Directory watching (new DICOM files trigger automatic conversion)
- Configurable FHIR client with circuit-breaker retry
- Embedded FHIR server for local dev/testing
- 162 tests, CI on 4 Python versions

Would love feedback from people who've dealt with similar pipelines in production. What failure modes am I not covering?

https://github.com/xxxn3m3s1sxxx/dicom-fhir-resilient-bridge

Also maintaining awesome-healthtech-engineering — a curated list of HealthTech open-source tools focused on engineering quality: https://github.com/xxxn3m3s1sxxx/awesome-healthtech-engineering

---

## LinkedIn DM (SABES contact)

Hi [Name],

I've been working on a DICOM → FHIR pipeline for resilient medical image exchange and just released it as open source. It's designed for production use with circuit-breaker patterns, directory watching, and extensive testing (162 tests across Python 3.10–3.13).

Since SABES/South Tyrol runs multiple hospitals, I'd love to hear your perspective — what does your current DICOM-to-FHIR workflow look like, and what failure scenarios are most painful?

https://github.com/xxxn3m3s1sxxx/dicom-fhir-resilient-bridge

---

## FHIR Zulip — DICOM channel

**Subject:** dicom-fhir-resilient-bridge — seeking co-maintainers

I built a resilient DICOM → FHIR bridge in Python. It watches directories, handles transient failures, and runs in 4 modes (oneshot, server, watcher, demo). 162 tests, all green.

Looking for people interested in DICOM/FHIR interop to co-maintain and extend it — especially adding DICOMweb endpoints and bulk data export.

https://github.com/xxxn3m3s1sxxx/dicom-fhir-resilient-bridge
