# FSP-19: Passenger Details: First Name is not mandatory and booking is confirmed with an empty First Name

| Field | Value |
|---|---|
| Priority | Medium |
| Labels | validation, passenger-details, functional, flight-booking |
| Status | Open |
| Environment | https://travel.agileway.net / browser and version not specified / OS not specified |

## Steps to reproduce
1. Log in to the application.
2. Start a flight booking and reach the passenger details page.
3. Leave the First Name field empty.
4. Enter a value in the Last Name field (tested with 1).
5. Click Next and complete the booking.

## Expected result
First Name is mandatory. A validation message is shown and the user cannot proceed until it is entered.

## Actual result
The system accepts an empty First Name and the booking is confirmed.

## Evidence
The source report references FSP-19.png; the image was not present in the supplied ZIP.

## Related
FSP-18 (numeric Last Name accepted)
