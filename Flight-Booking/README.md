# Flight Booking Application: Manual QA Project

Manual testing project for the Agile Travel flight booking web application (https://travel.agileway.net), covering test planning, test case design in Zephyr, additional test case design, and defect reporting in Jira.

**Author:** Kingstan Nadar  
**Role:** Manual Tester

## Project at a glance

| Item | Detail |
|---|---|
| Application under test | Agile Travel (travel.agileway.net) |
| Testing type | Manual: functional, negative, boundary, usability, responsive |
| Test management | Zephyr (inside Jira): 33 test cases |
| Additional test cases designed | 46 (CSV tracker) |
| Total test cases designed | 79 |
| Defects reported | 3 (FSP-17, FSP-18, FSP-19) |

## Repository contents

- [Test Plan](docs/01-test-plan.md)
- [Traceability Matrix](docs/02-traceability-matrix.md)
- [Test Summary Report](docs/03-test-summary-report.md)
- [Existing Zephyr Test Cases](test-cases/existing-zephyr-test-cases.md)
- [46 Additional Test Cases (CSV)](test-cases/new-test-cases.csv)
- [Bug Summary](bug-reports/bug-summary.md)
- [FSP-17](bug-reports/FSP-17.md)
- [FSP-18](bug-reports/FSP-18.md)
- [FSP-19](bug-reports/FSP-19.md)
- [Screenshot Evidence Notes](screenshots/README.md)

## What is covered

- **Search and select flight:** one-way and round-trip scenarios, invalid route/date inputs, responsive layout, multiple passengers and flight selection.
- **Passenger details:** valid and invalid names, mandatory fields, and passenger information.
- **Payments:** card types, payment amount, and negative validation scenarios for card number, expiry date, CVV and cardholder details.
- **Booking confirmation:** confirmation details and post-payment navigation.
- **Cancellation and session:** cancellation, session timeout and seat-selection scenarios.

## Defects reported

| Bug ID | Summary | Priority | Status |
|---|---|---|---|
| [FSP-17](bug-reports/FSP-17.md) | No option to return to booking page after successful payment | Medium | Open |
| [FSP-18](bug-reports/FSP-18.md) | Last Name field accepts numeric values and allows user to proceed | Medium | Open |
| [FSP-19](bug-reports/FSP-19.md) | First Name is not mandatory; booking confirmed with an empty First Name | Medium | Open |

## Execution status note

The CSV tracker contains 46 additional cases: 2 marked **Fail** and 44 marked **Not Executed**. The separate test summary reports 33 cases in Zephyr and 46 additional cases designed, but its overall Zephyr execution totals are left blank. Therefore, 79 is the number of cases designed/recorded across the two sources, not a claim that all 79 were executed. The three reported defects are documented separately.

The supplied ZIP contains a screenshot README with expected image names, but the PNG evidence files themselves were not included.

## Skills practised

Test planning, test case design, positive and negative testing, boundary-value analysis, equivalence partitioning, defect reporting, traceability, Jira, Zephyr, and Excel-based execution tracking.
