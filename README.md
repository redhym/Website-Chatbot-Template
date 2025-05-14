# Website Chatbot Template (No-Code HTML)

This is a lightweight, floating chatbot built using just HTML, CSS, and JavaScript.  
It's designed to help small businesses or creators collect customer data, take orders, or handle basic FAQs — without any frameworks or backend setup.

---

## Features

- Fully customizable chatbot UI
- Step-by-step conversation flow
- Order and registration support
- Connects to Google Sheets via Apps Script
- No frameworks, no build tools — just drop-in HTML

---

## What’s Included

- `index.html` — the full working chatbot code
- `setup_guide.pdf` — step-by-step instructions for use and Google Sheets integration

---

## How to Use

1. Download or clone the repo
2. Open `index.html` in your browser to test it
3. To use on your site:
   - Copy the `<div>` and `<script>` blocks into your webpage
   - Or upload the file as-is and host it directly

---

## Optional: Google Sheets Integration

To save customer or order data:
- Deploy your own [Google Apps Script](https://script.google.com)
- Set permissions to "Anyone"
- Replace this line in the code:

```javascript
const url = "INSERT_YOUR_SCRIPT";
