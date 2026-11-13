# Day 9 — 4 September 2026
## Building the Donation Tracker JavaScript foundation

I began implementing the Donation Tracker’s browser-side JavaScript in `app.js`. I configured the backend base URL and Cardano settings, then added helper functions to display status messages, send and receive JSON through HTTP requests, and escape text before displaying it on the page.

I also implemented the retrieval and display of donation records in a table, formatted the total donation amount in rand, and added empty and error states. These functions connect the interface to backend services and present donation information clearly when records are available or when a request returns no results or an error.

## Tools and technologies

- JavaScript
- HTTP and JSON
- Cardano settings
- Browser-based user interface

## Evidence

- [Donation Tracker JavaScript: configuration, helpers, and donation display](https://github.com/KamogeloMoruri/-Coxy-wallet/blob/main/WIL%202%20work/app%20%281%29.js#L1-L104)
