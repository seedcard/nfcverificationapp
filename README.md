Upgraded version of SEEDCARD verification - a webapp that works with encoded NFC NTAG424 tags

Each tag is encoded with: Redirect URL + query containing unique 14 digit UID

UID is cross-referenced with list of UID codes held in a JSON file

Verified UID can access link to wallet address to check BTC balance (this card is unfunded)

Example of verified UID - https://seedcard.github.io/nfcverificationapp/index.html?uid=0442157A4F1390

Unverified UID can click link to send email with UID code to seedcard team

Example of unverified UID - https://seedcard.github.io/nfcverificationapp/index.html?uid=0430167A4F1390

This app is work in progress - the direct tap to scan of NFC tag is not working yet!



