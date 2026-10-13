# Getting started

GDPR Compliance Scanner is a browser-local screening tool for spotting likely personal data before a file is shared, uploaded or archived. It supports common document and data formats, reports heuristic findings and keeps the inspected content in the browser.

## Try it

Open the [live scanner](https://jeevan-0508.github.io/gdpr-compliance-scanner/). Use the synthetic demo screenshots as a guide, upload a file only when you understand the browser-local boundary, and inspect the results and limitations before taking action.

The tool is a linter for personal data, not a GDPR compliance assessment. A finding requires human review; an empty result is not proof that a file contains no personal data.

## Run locally

Serve the static files over HTTP:

```bash
python3 -m http.server 4173
```

Open <http://localhost:4173/>; it redirects to `gdpr_scanner.html`.

## Privacy boundary

The application is designed to process files in the browser and does not include an application server. Review the browser, deployment and third-party asset assumptions before using it with sensitive material.
