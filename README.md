https://explorer.solana.com/tx/4aLaWDAqVWCdgWyHbToxUet8YFvoeNRPAbYskGorPMqkHXsqGcsavUVtYGEMuaSiGxXbq5dny9cyT2F12F9qVtVc?cluster=devnet

There are 3 scripts in here:

keygen.ts: This is used to generate a new wallet, and logs its public and secret keys. To run the script, use "yarn keygen"

transfer.ts: This is used to transfer tokens on the devnet. To run, simply use "yarn transfer"

enroll.ts: This script uses the Anchor framework with Solana's web3.js. It completes a prerequisite enrollment process for the program WbaPrereq using a specified GitHub username (github). It signs transactions, verifies with Solana, and outputs the transaction hash upon success.

After cloning, "yarn install"
