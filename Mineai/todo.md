# MineGov AI CRM Expansion Checklist

## Duplicate-key repair

- [x] Trace the root-page warning to the exact mapped list and key expression.
- [x] Replace the non-unique key with a stable unique key without changing visible behavior.
- [x] Run TypeScript/build checks and verify the root page has no duplicate-key warning.


- [x] Add CRM navigation entry and route/view state to the existing persistent sidebar.
- [x] Add CRM KPI summary cards for ACV, weighted pipeline, client health, and renewals.
- [x] Add functional CRM view modes: pipeline, accounts, stakeholders, and contracts.
- [x] Add search and segment/tier/lead-owner filtering.
- [x] Add responsive Kanban pipeline with stage totals and drag/drop stage updates.
- [x] Add enterprise accounts table with quick actions.
- [x] Add Account 360 drawer with overview, stakeholders, activity timeline, and usage tabs.
- [x] Make meeting-note logging append to the selected account timeline with a current timestamp.
- [x] Add functional client-directory CSV export and simulated CRM disclaimer watermark.
- [x] Validate CRM flow, build, responsiveness, and preserve existing risk-to-action-to-audit workflow.
