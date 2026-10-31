# Business Tracker (phone app)

A small installable web app for tracking **orders** and **action items** across multiple businesses.

## Features
- Add any number of businesses, each with its own color
- Orders: customer, order #, items, amount, status (New → In Progress → Shipped → Delivered / Cancelled), order date, due date, tracking/notes
- Action items per business: due date, priority, notes, check off when done
- Home dashboard: open orders, open order value, late orders, overdue action items, per-business summary
- Filter everything by business with the chips at the top
- Works offline; data stays on your phone
- Export/Import backup (Businesses tab), so you can move to a new phone or keep a safe copy

## Putting it on your phone
1. Host this folder anywhere that serves HTTPS (e.g. enable GitHub Pages on this repo, or drag the folder into Netlify).
2. Open the URL on your phone:
   - **iPhone (Safari):** Share → *Add to Home Screen*
   - **Android (Chrome):** ⋮ menu → *Add to Home screen* / *Install app*
3. It opens full-screen like a regular app.

Data is stored in the phone's browser storage for that app. Use **Export backup** regularly.
