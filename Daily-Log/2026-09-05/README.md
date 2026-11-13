# Day 10 — 5 September 2026
## Implementing the donation form and AI question handler

I implemented JavaScript handlers for the Donation Tracker’s rand donation form and AI question feature. For the donation form, I prevented the page from reloading, read the donor’s name, donation amount, and purpose, checked that the required fields were completed, and sent the information to the backend as JSON.

After a donation was saved successfully, the interface displayed a confirmation, reset the form, and refreshed the donation list. I also implemented the AI question handler to check that a question had been entered, send it to the backend, and display the returned answer or an error message.

## Tools and technologies

- JavaScript
- HTML forms
- HTTP requests and JSON
- Backend API

## Evidence

- [Donation Tracker JavaScript: donation form and AI assistant](https://github.com/KamogeloMoruri/-Coxy-wallet/blob/main/WIL%202%20work/app%20%281%29.js#L106-L154)
