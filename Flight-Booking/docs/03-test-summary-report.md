# Test Summary Report: Flight Booking

**Project:** Flight Booking (FSP)  
**Application:** https://travel.agileway.net  
**Tester:** Kingstan Nadar

## 1. Test coverage

| Metric | Count |
|---|---:|
| Test cases in Zephyr (reported by source summary) | 33 |
| Additional test cases designed (CSV) | 46 |
| Total test cases designed/recorded | 79 |
| Defects reported | 3 |

## 2. Execution results

The source summary does not provide consolidated Zephyr execution totals. Do not infer pass/fail totals for all 79 cases.

The additional CSV tracker contains:
| Status | Count |
|---|---:|
| Fail | 2 |
| Not Executed | 44 |
| **Total additional cases** | **46** |

## 3. Defect summary

| Bug ID | Summary | Priority | Status |
|---|---|---|---|
| FSP-17 | No option to return to booking page after successful payment | Medium | Open |
| FSP-18 | Last Name field accepts numeric values and allows user to proceed | Medium | Open |
| FSP-19 | First Name not mandatory; booking confirmed with an empty First Name | Medium | Open |

The supplied project report states that all three defects were retested on 04-Nov-2026 and were still reproducible.

## 4. Observations
- Payment validation coverage includes 12 negative scenarios in the existing Zephyr coverage description.
- Passenger-detail validation issues are documented: numeric Last Name and empty First Name are accepted.
- The post-payment page gives the user no way to book another flight.

## 5. Recommendation
Fix the passenger-detail validation (FSP-18, FSP-19) and add navigation after payment (FSP-17), then retest and close the defects.
