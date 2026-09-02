# GDPR Compliance Scanner

A client-side HTML tool to scan data files for GDPR compliance risks — no server, no upload, runs entirely in the browser.

## Features

- **Drag & drop** CSV, Excel (.xlsx/.xls), JSON, TXT, TSV files
- **Two-pass detection:**
  - Header name analysis against 29 GDPR rules
  - Value-level regex scanning across up to 2,000 rows (9 pattern types)
- **Detects:** emails, IBANs, credit cards, UK NI numbers, phone numbers, GPS coordinates, dates of birth, passport numbers, IP addresses, and Art. 9 special categories (health, race, religion, biometric, genetic, criminal conviction data)
- **Risk levels:** Critical / High / Medium / Low mapped to GDPR articles
- **Dashboard output:**
  - GDPR Risk Score /100 with grade
  - KPI cards + donut chart by data type
  - GDPR compliance checklist (6 checks)
  - Sortable, filterable findings table with article references and remediation advice
  - Export to standalone HTML report

## Usage

1. Open  in any modern browser
2. Drag & drop a file (or click Browse)
3. Review findings, adjust controls, export report

## Privacy

All processing happens locally in the browser. No data is sent to any server.

## GDPR Coverage

| Risk | Data Types |
|------|-----------|
| Critical | Health, racial/ethnic origin, religion, political opinion, sexual orientation, criminal conviction, biometric, genetic (Art. 9 & 10) |
| High | National ID, passport, email, phone, DOB, full name, address, IBAN, credit card, salary |
| Medium | IP address, GPS/location, device ID, cookie/session ID, demographic data, nationality, photos |
| Low | Record identifiers, timestamps, free text/notes |

## Screenshots

*(Drop a screenshot here after first use)*
