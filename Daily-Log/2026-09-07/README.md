# Day 12 — 7 September 2026
## Implementing Cardano transaction verification

I implemented the Donation Tracker’s transaction verification handler. It reads the transaction ID entered by the user, checks that the field is not empty, and sends the ID to the backend for verification. While the request is processing, the interface displays a status message.

When the backend confirms a transaction, the page displays the confirmed ADA amount and reloads the donation records. If the transaction is not verified or the request fails, the interface displays the reason or error message. This feature gives users feedback about the status of a submitted transaction.

## Tools and technologies

- JavaScript
- HTTP requests and JSON
- Backend transaction verification
- Cardano transaction ID

## Evidence

- [Donation Tracker JavaScript: transaction verification handler](https://github.com/KamogeloMoruri/-Coxy-wallet/blob/main/WIL%202%20work/app%20%281%29.js#L212-L229)
