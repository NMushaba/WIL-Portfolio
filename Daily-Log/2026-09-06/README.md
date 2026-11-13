# Day 11 — 6 September 2026
## Implementing Cardano wallet connection and ADA donations

I extended the Donation Tracker’s JavaScript to support Cardano wallet connection and ADA donations. The wallet handler checks for compatible wallet extensions, connects to an available wallet through the Cardano off-chain module, and displays the connection result in the interface.

I also added checks to ensure that a wallet was connected and that the ADA donation amount was a valid positive number before calling the off-chain donation function. After submission, the interface displays the transaction hash or an error message and refreshes the donation list. This work connected the Donation Tracker interface to its wallet-based donation process.

## Tools and technologies

- JavaScript
- Cardano wallet extensions
- Cardano off-chain module
- ADA

## Evidence

- [Donation Tracker JavaScript: wallet connection and ADA donation handlers](https://github.com/KamogeloMoruri/-Coxy-wallet/blob/main/WIL%202%20work/app%20%281%29.js#L157-L210)
