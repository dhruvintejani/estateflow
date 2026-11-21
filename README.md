# EstateFlow

A frontend-only real estate CRM prototype built with React, Vite, Lucide, Recharts and jsPDF. The workspace includes synthetic sample data, 16 staff records, lead management, drag-and-drop pipeline, inventory, local inbox simulations (Instagram, Facebook, WhatsApp, website and email), site visits, follow-ups, PDF quotations, bookings, document metadata and reports.

## Run locally

```sh
npm install
npm run dev
```

Production build: `npm run build`. Preview the build with `npm run preview`.

## Deploy
Import this repository into Vercel, use the Vite framework preset and deploy the `main` branch. Build command: `npm run build`; output directory: `dist`. No environment variables or backend required.

## Presenting the prototype
Open Unified inbox, choose Simulate enquiry, select Instagram and enter a fictional message. The app creates a conversation and a lead; automatic assignment selects an active staff member with the fewest open leads. Open the lead to schedule visits, follow-ups, quotations or bookings. Confirmed bookings update local property availability. Reports reflect local records. Quotation PDF and CSV export are generated in-browser.

This is a local browser prototype, not a live customer system. All messages, replies, integrations and payments are simulated or manually recorded. No external accounts are connected and no messages are actually sent. LocalStorage is not secure storage; use fictional information only. Document management stores metadata, not uploaded files. No real authentication or role-based permission system is included. Use Settings > Reset sample data to restore the initial workspace.
