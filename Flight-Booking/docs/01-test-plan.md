# Test Plan: Flight Booking Application

## 1. Objective
Verify that the Agile Travel flight booking flow (search, passenger details, payment, confirmation) works as expected and that invalid input is handled correctly.

## 2. Scope
**In scope:** flight search and selection, passenger details, payment, booking confirmation, responsive layout of the Select Flight page.  
**Out of scope:** performance and load testing, security testing, API testing, automation.

## 3. Test approach
Manual testing using:
- Functional testing (valid flows)
- Negative testing (invalid and empty inputs)
- Boundary value analysis and equivalence partitioning (card number, names, dates)
- Usability and navigation checks (post-payment flow)
- Responsive layout check

## 4. Test environment
| Item | Detail |
|---|---|
| Application | https://travel.agileway.net |
| Browser(s) | Not specified in the supplied project files |
| OS | Not specified in the supplied project files |
| Test data | Demo account shown on the login page; sample card details as required |

## 5. Tools
Jira (defect tracking), Zephyr (test case management and execution), MS Excel (execution tracker).

## 6. Test deliverables
Test plan, test cases (Zephyr and CSV), bug reports, traceability matrix, test summary report.

## 7. Entry criteria
- Application is accessible and login works.
- Test cases are reviewed and available in Zephyr.

## 8. Exit criteria
- All planned test cases are executed.
- All defects are logged in Jira with evidence.
- No open High-severity defects, or they are documented and accepted.

## 9. Defect management
Defects are logged in Jira with reproduction steps, expected and actual results, priority, labels and screenshots. Life cycle: To Do, In Progress, Done (after a verified retest).

## 10. Risks and assumptions
- The application is a public practice site, so defects may not be fixed.
- Test data and behaviour may change without notice.
