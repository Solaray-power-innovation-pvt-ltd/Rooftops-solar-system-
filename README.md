# Solaray Power Innovations Private Limited Website

A responsive static-style company website with a small Node.js server. It uses the supplied Solaray logo and wordmark images.

## Files

- `index.html` — page structure and company information
- `styles.css` — responsive layout, colours and styling
- `script.js` — mobile navigation, current year and enquiry form behaviour
- `server.js` — lightweight Node.js web server
- `solaray-logo.jpg` — supplied circular logo
- `solaray-wordmark.jpg` — supplied company wordmark

## Run locally

1. Install Node.js (version 18 or newer recommended).
2. Extract this ZIP file.
3. Open a terminal in the extracted folder.
4. Run:

   ```bash
   node server.js
   ```

5. Open `http://localhost:3000` in your browser.

You can also open `index.html` directly, although running the server is recommended.

## Enquiry form

The form validates the required fields in the browser and opens WhatsApp with a prefilled message to **+91 93664 95875**. The visitor must review and send the message in WhatsApp. This demo does not collect, store, or transmit form submissions to a website database.

## Before publishing

- Verify company details, contact numbers, address, service descriptions and opening hours.
- Only publish claims such as government/MNRE/TSECL authorisation if you have verified documentation and permission to make those claims. This template intentionally does not state that approval is verified.
- Add a privacy policy if you add analytics, tracking or a backend form handler.
- Deploy the folder to your preferred hosting provider or configure the Node server on a supported host.

## Customisation

Update the content in `index.html`, the colours in `styles.css`, and the WhatsApp number in `script.js` if the company confirms a different enquiry number.
