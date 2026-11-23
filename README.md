<img src="assets/icon.svg" width="64" height="64" alt="">

# ynab-helpers

Chrome extension that fills empty YNAB memos for:

- **Amazon** transactions: the product names, ship-to name and city, orderer,
  and a link to the order.
- **Venmo** transactions: who you paid and the Venmo note, or the bank of a
  transfer.

It uses your own logged-in sessions on amazon.com, venmo.com, and
app.ynab.com. No API keys, no servers; data stays in `chrome.storage.local`.

## Install

1. Open `chrome://extensions` and turn on **Developer mode**.
2. Click **Load unpacked** and select the `extension/` folder.
