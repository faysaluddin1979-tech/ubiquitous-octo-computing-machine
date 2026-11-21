# MONI CCM Dashboard V2

A standalone, browser-based chronic care management (CCM) dashboard prototype for demonstrating a fictional patient workflow.

**Demo only:** Never enter real patient information. This prototype has no secure authentication, server database, HIPAA controls, or OmniMD integration. It is not for patient care or billing.

## Run the dashboard

Download or clone this repository and open `MONI_CCM_Dashboard_V2.html` in a modern browser with JavaScript enabled. No installation or server is required.

## What it demonstrates

- Enrolling fictional patients and recording simulated consent and care plans.
- Logging demo activities and reviewing time totals, a billing checklist, and monthly summaries.
- Printing a report, exporting demo records as JSON, and resetting saved demo records.

Records are stored in the browser's local storage on the current device, not in a shared database. The reset button clears the dashboard's saved demo records. Exported JSON files are separate and must be deleted manually.

Billing review does not generate or submit claims, and logged minutes alone do not establish billing eligibility.
