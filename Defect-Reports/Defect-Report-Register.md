# Defect Register

This register reflects the latest reviewed workbook observations. Items with unconfirmed requirements are deliberately kept as pending and are not presented as confirmed defects.

## DEF-RESERVE-001 — Reservation -> Tomorrow's check-in date is accepted

- **Module:** Reservation / Check-in Date Validation
- **Status:** FAIL / Open for investigation
- **Related test cases:** TC-RESERVE-035 and TC-RESERVE-117
- **Observed behaviour:** The application accepted a check-in date of tomorrow.
- **Expected behaviour:** The check-in date should follow the project's stated booking-window rule.
- **Note:** The reviewed workbook identifies 1 November 2026 as the earliest permitted date and records 31 October 2026 (tomorrow) as accepted. Confirm the rule against the approved requirements before final severity assignment.

## Guest name input observations — Pending requirement confirmation

The reviewed workbook records acceptance of the following guest-name inputs:
- Spaces only (TC-RESERVE-085)
- Numeric only (TC-RESERVE-086)
- Symbols only (TC-RESERVE-087)
- Numbers and symbols only (TC-RESERVE-088)

**Status:** Pending. The allowed-character requirement for guest names has not yet been confirmed. Do not report these as confirmed defects until the expected validation rule is established.

## Defect reporting standard

Use the title format `Section -> Short Summary`. Include steps to reproduce, expected result, actual result, severity, priority, status, and related test case IDs. Assign severity and priority only when supported by impact and requirements.

The master workbook remains the source of detailed test execution and defect records.
