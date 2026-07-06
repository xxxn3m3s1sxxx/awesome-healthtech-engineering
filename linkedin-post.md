We just open-sourced a DICOM → FHIR bridge designed for production.

Key numbers:
• 162 tests across Python 3.10–3.13
• 4 operating modes (oneshot, server, directory watcher, demo)
• 67 bug-hunt rounds each in 2 independent runs
• Circuit breaker with configurable retry policy
• CI that runs every push

Why build this?
Most DICOM-to-FHIR scripts work great — until the FHIR server goes down, or a DICOM file is half-written, or the disk fills up. This bridge treats those as design requirements, not edge cases.

The stack: Python, pydicom, aiohttp, watchdog, pytest.

We also keep awesome-healthtech-engineering — a curated list of open-source HealthTech tools focused on production-grade engineering. PRs welcome.

https://github.com/xxxn3m3s1sxxx/dicom-fhir-resilient-bridge
https://github.com/xxxn3m3s1sxxx/awesome-healthtech-engineering

#HealthTech #FHIR #DICOM #OpenSource #MedicalImaging #Python
