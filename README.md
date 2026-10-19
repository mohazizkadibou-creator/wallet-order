# Solana Wallet Report — order form

Static, zero-dependency order form (Arabic/English) for the $19 Solana wallet activity report.

- Validates Solana public addresses (base58, 32–44 chars) before accepting an order.
- Packages: $19 single, $29 double, $39 rush.
- Builds an order message and copies it to the clipboard, then opens Telegram/WhatsApp/email
  if a contact is configured in the `CFG` object at the bottom of `index.html`.
- Never asks for seed phrases or private keys; no wallet connection.

Run locally: open `index.html` in any browser.
