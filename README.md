# CampusFix Campus Maintenance Manager

A Zoho Creator demonstration for reporting campus issues, coordinating repair teams, and monitoring maintenance progress.

## Project contents

- [Project report](PROJECT_REPORT.md): aim, data model, procedure, validation rules, observations, limitations, and demonstration script.
- `Maintenance_Requests.ds`: saved form definition.
- `Validate_Maintenance_Requ.ds`: saved add or edit validation workflow.
- `All_Maintenance_Requests.ds`: list report definition.
- `Repair_Status_Board.ds`: Kanban report definition grouped by Status.
- `CampusFix_Dashboard.zml`: dashboard layout wrapper; its referenced HTML Snippet is not included.
- `dashboard.jpg`: live browser evidence.

## Features

Capture issues across Electrical, Plumbing, Network, Furniture, and Cleaning. Set Low, Medium, or High priority. Track Reported, Assigned, In Progress, and Resolved requests. Validate dates, descriptions, team assignments, and resolution notes.

Reviewed on 2 November 2026: 8 fictional requests, with status counts 1 / 3 / 2 / 2 and 1 overdue unresolved request. See the report for verification scope.

## Using the source

These are Zoho Creator component definitions captured from the Application IDE, not a standalone web application or complete importable backup. Review the form first, then the validation workflow and reports in a test Creator application. The Kanban board uses the Status field. A full dashboard rebuild also needs the HTML Snippet implementation. No local build or deployment pipeline is provided.

## Reference

Report organization follows the academic record style in [san342147/CB23F35-Low-Code-Zoho-Creator](https://github.com/san342147/CB23F35-Low-Code-Zoho-Creator). Findings and source files describe CampusFix; this repository does not reproduce the reference lab records.
