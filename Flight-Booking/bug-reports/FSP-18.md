# FSP-18: Passenger Details: Last Name field accepts numeric values and allows user to proceed

| Field | Value |
|---|---|
| Priority | Medium |
| Labels | validation, passenger-details, functional, flight-booking |
| Status | Open (reproduced 04-Nov-2026) |
| Environment | https://travel.agileway.net / browser and version not specified / OS not specified |

## Steps to reproduce
1. Open the passenger details page.
2. Enter a numeric value (for example 1) in the Last Name field.
3. Fill the First Name field with a valid name.
4. Click Next.

## Expected result
The system shows an error message and blocks the user when the Last Name contains numeric values.

## Actual result
The system accepts numeric values in Last Name and lets the user proceed without any error. On retest the booking was confirmed.

## Evidence
The source report references FSP-18.png; the image was not present in the supplied ZIP.

## Related test cases
FSP-T17, FSP-T18, TC-IP-01, TC-IP-02
