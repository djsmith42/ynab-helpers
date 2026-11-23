# YNAB Helpers Chrome Extension

This makes it much easier to categorize Amazon and Venmo transactions in YNAB

<img width="1281" height="732" alt="image" src="https://github.com/user-attachments/assets/6e04664d-3b65-4a8b-812a-4aa0d97ef508" />

<img width="1282" height="732" alt="image" src="https://github.com/user-attachments/assets/b9830250-ecdc-4175-8d51-2571cf78fe27" />




- **Amazon** transactions: the product names, ship-to name and city, orderer,
  and a link to the order.
- **Venmo** transactions: who you paid and the Venmo note, or the bank of a
  transfer.

It uses your own logged-in sessions on amazon.com, venmo.com, and
app.ynab.com. No API keys, no servers; data stays in `chrome.storage.local`.

## Install

1. Open `chrome://extensions` and turn on **Developer mode**.
2. Click **Load unpacked** and select the `extension/` folder.
