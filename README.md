# PureFlow — Purified Water Ordering System

A complete React + Vite demo with a fresh teal/mint UI, 2L/5L/10L can selection, custom liters, automatic price calculations, optional delivery, payment choices, customer form, and printable bill.

## Run
1. Extract the ZIP.
2. Open the `PureFlow-Water-Delivery` folder in VS Code (the folder containing `package.json`).
3. Run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL shown by Vite, usually `http://localhost:5173`.

## Features
- Select quantities of 2L, 5L and 10L water cans.
- Custom quantity entry from 1 to 500 liters.
- Automatic calculation at ₹4 per liter.
- Optional flat ₹25 doorstep delivery charge.
- Name, phone and address validation.
- UPI/QR, card and cash-on-delivery choices.
- Confirm order to generate an itemized bill and order number.
- Print / Save bill using the browser print dialog.
- Responsive, modern layout.

## Demo limitation
This is a front-end demo. It does not connect to a real payment gateway, backend, supplier, or dispatch service. No real payment is collected and no delivery is actually scheduled.
