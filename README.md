# QR Food System MVP

A prompt-engineered MVP demo exploring how QR menus can evolve into branded, restaurant-owned food ordering systems.

Most cafés have shifted to QR menus, but many QR menus are still just PDF links. A customer scans the QR code, opens the menu, checks items, and still has to call the waiter to place the order.

This project explores a better version: a QR-based food system where the QR code becomes the entry point into the café’s own branded digital experience.

## Project Positioning

This is an AI-assisted MVP prototype created through structured prompt engineering and product thinking.

The focus is not manual full-stack development. The focus is:

- identifying a real user-experience problem
- framing the customer and restaurant-owner workflows
- writing a detailed product prompt
- using AI-assisted prototyping to generate a clickable MVP demo
- documenting the product logic, scope, and future direction

## Core Idea

The QR code is not the product. It is only the entry point.

The real product is a restaurant-owned digital food system where customers can scan a table QR, browse the café’s branded menu, customize items, add items to cart, place orders, and send them directly to the kitchen/dashboard.

## Demo Restaurant

The MVP uses a fictional café called **Saajh Café** — a warm, premium, modern Indian café built around slow evenings, conversations, focused work, and comfort food.

## Customer Benefits

- No need to wait for a waiter
- Easier menu browsing
- Faster ordering
- Fewer communication errors
- Better food discovery through images and categories
- More premium café experience

## Restaurant Owner Benefits

- Reduced waiter dependency
- Fewer order mistakes
- Faster service
- Direct customer data
- Direct booking capture
- Better upselling opportunities
- Stronger digital brand experience
- Reduced dependency on third-party platforms

## MVP Features

- QR-based table ordering
- Branded café menu page
- Menu categories
- Food item cards
- Add to cart
- Order placement
- Kitchen/dashboard order view
- Order status tracking
- Direct booking form
- Basic customer data view
- Basic analytics dashboard

## Demo Routes

- `/` — product landing page
- `/demo` — demo selection page
- `/r/saajh-cafe/table/7` — customer QR ordering demo
- `/r/saajh-cafe/book` — direct table booking demo
- `/dashboard` — restaurant dashboard overview
- `/dashboard/orders` — live order board
- `/dashboard/kitchen` — kitchen display
- `/dashboard/menu` — menu management
- `/dashboard/tables` — QR table management
- `/dashboard/bookings` — direct booking management
- `/dashboard/customers` — customer data view
- `/dashboard/analytics` — basic analytics and ROI view
- `/dashboard/branding` — branding preview

## Tech Stack

- React
- Vite
- CSS
- LocalStorage / mock data for demo state
- AI-assisted prototyping workflow

## Run Locally

```bash
npm install
npm run dev
```

Then open the local Vite URL shown in the terminal.

## Documentation

The `docs/` folder includes:

- problem statement
- product thinking
- prompt engineering process
- customer flow
- restaurant owner flow
- MVP scope
- Saajh Café demo profile
- future scope

## Future Scope

- Online payments
- Loyalty system
- Personalized offers
- WhatsApp updates
- AI-based upselling
- Inventory management
- POS integration
- Multi-branch dashboard
- Customer retention campaigns

## Status

Currently in MVP/demo stage.

## Note

This project is presented honestly as a prompt-engineered, AI-assisted MVP demo. It is not claimed as a production-ready SaaS or a manually coded full-stack application.
